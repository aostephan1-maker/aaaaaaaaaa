## 使用本地域名访问 cloud ide 开发环境

点击 Cloud Ports 面板中的 Proxy to local，会在剪贴板中插入一条 Shell 命令，将该命令粘贴到本地电脑的 Terminal 中并执行，就可以以本地域名的方式访问 cloudide 的内容。

![Step 1](/docs/cloud-ide-1.png "Step 1")
![Step 2](/docs/cloud-ide-2.png "Step 2")

## 使用线上域名联调基座本地代码

在 source 面板，开启 overrides 功能。

启动 framework 的 dev 模式，然后把 localhost:8000 对应的 html 拷贝出来，对你将要访问页面 url 的 html 内容进行 override

## 项目命令

可以查看 [在线文档](https://bytedance.feishu.cn/wiki/wikcno6kgJv7axIOEiSNhpUbWSd)

### 添加物料

```shell
pnpm run add:material
```

### 只启动基座，业务模块访问线上资源

```shell
pnpm run dev:framework
```

### 只启动单一业务模块，基座访问线上资源

```shell
pnpm run dev:pipeline
```

### 本地联调单一业务模块和基座，访问业务模块端口

```shell
# 需要开两个终端，分别执行
pnpm run dev:pipeline:frame

pnpm run dev:framework

```

### 本地联调所有业务模块和基座

> 针对同时启动多个模块的场景，跨仓库的模块不支持，会加载线上资源

```shell
pnpm run dev:all
```

### 本地调试物料

```shell
pnpm run dev:materials
```

### 发布正式物料包

```shell
pnpm run publish:materials
```

### 发布测试物料包

```shell
pnpm run publish:materials-beta
```

## 命令速查表

<table cellpadding="8" cellspacing="0" border="1" style="border-collapse:collapse;width:100%;font-size:14px;">
  <thead>
    <tr style="background:#f2f3f5;">
      <th style="width:24%;text-align:left;">场景</th>
      <th style="width:32%;text-align:left;">命令</th>
      <th style="width:14%;text-align:left;">端口</th>
      <th style="text-align:left;">说明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2"><b>单模块开发</b></td>
      <td><code>pnpm run dev:framework</code></td>
      <td>8000</td>
      <td>只起基座，业务模块走线上</td>
    </tr>
    <tr>
      <td><code>pnpm run dev:pipeline</code></td>
      <td>—</td>
      <td>只起业务模块，基座走线上</td>
    </tr>
    <tr>
      <td><b>基座 + 单模块联调</b></td>
      <td>
        <code>pnpm run dev:pipeline:frame</code><br>
        <code>pnpm run dev:framework</code>
      </td>
      <td>双终端</td>
      <td>frame 模式 + 基座，访问业务模块端口</td>
    </tr>
    <tr>
      <td><b>全量联调</b></td>
      <td><code>pnpm run dev:all</code></td>
      <td>多端口</td>
      <td>跨仓库模块会回退到线上资源</td>
    </tr>
    <tr>
      <td><b>物料开发</b></td>
      <td><code>pnpm run dev:materials</code></td>
      <td>—</td>
      <td>监听 packages 变更并自动热重载上游</td>
    </tr>
    <tr>
      <td rowspan="2"><b>物料发布</b></td>
      <td><code>pnpm run publish:materials</code></td>
      <td colspan="2" style="text-align:center;background:#f7f8fa;">正式版</td>
    </tr>
    <tr>
      <td><code>pnpm run publish:materials-beta</code></td>
      <td colspan="2" style="text-align:center;background:#e8f3ff;color:#165dff;">Beta 测试版</td>
    </tr>
    <tr>
      <td><b>新增物料</b></td>
      <td><code>pnpm run add:material</code></td>
      <td colspan="2">脚手架引导创建新的 packages 物料</td>
    </tr>
  </tbody>
</table>

## 构建效率模型

本项目使用 Turborepo 做任务编排、Rspack 做极速构建，结合 Module Federation 实现微前端模块按需加载。以下用数学公式量化核心效率指标。

### 1. 并行构建加速比

设共有 $N$ 个任务，第 $i$ 个任务的串行耗时为 $t\_i$，且存在依赖关系 $D$ 决定关键路径长度 $T\_{\text{critical}} = \sum\_{i \in \text{critical path}} t\_i$。

Turborepo 将任务调度到 $P$ 个并行 worker 上，实际总构建时间为：

$$
T\_{\text{parallel}} = \max\left(T\_{\text{critical}},\ \frac{1}{P}\sum\_{i=1}^{N} t\_i\right)
$$

加速比（Speedup）定义为：

$$
S = \frac{T\_{\text{serial}}}{T\_{\text{parallel}}} = \frac{\sum\_{i=1}^{N} t\_i}{\max\left(T\_{\text{critical}},\ \frac{1}{P}\sum\_{i=1}^{N} t\_i\right)}
$$

其中 $1 \le S \le P$，关键路径越短、并行度越高，加速效果越显著。

### 2. 缓存命中后的构建时间

令本地缓存命中率为 $h \in \[0, 1]$，远程（云）缓存命中率为 $r \in \[0, 1]$，未命中时的重建耗时基线为 $T\_{\text{build}}$，命中后恢复耗时为 $T\_{\text{restore}} \ll T\_{\text{build}}$。

期望构建时间：

$$
\mathbb{E}\[T] = (1 - h)(1 - r),T\_{\text{build}} + \left\[h + (1 - h)r\right]T\_{\text{restore}}
$$

引入缓存节省比 $K = \frac{T\_{\text{restore}}}{T\_{\text{build}}}$（通常 $K < 0.1$），可化简为：

$$
\mathbb{E}\[T] = T\_{\text{build}} \cdot \left\[(1 - h)(1 - r) + K(h + r - hr)\right]
$$

### 3. 微前端模块加载总量

用户访问一个路由时，设基座体积为 $B$，该路由下共加载 $M$ 个远程模块，每个模块体积为 $V\_j$，公共依赖体积为 $C$，共享比例为 $\alpha$（即被多个模块复用并只下载一次的比例）。

实际网络传输总字节数为：

$$
\text{Payload} = B + \sum\_{j=1}^{M} V\_j - \alpha \cdot \sum\_{j=1}^{M} V\_j + (1 - \alpha)C
$$

当 $\alpha \to 1$（公共依赖完全共享）时：

$$
\text{Payload} \approx B + (1 - \alpha)\sum\_{j=1}^{M} V\_j + C ;\to; B + C
$$

即传输体积趋近于"基座 + 公共依赖"，这是 Module Federation 架构的理想上限。

### 4. 热更新延迟

HMR 延迟由三部分组成：文件系统检测 $t\_{\text{fs}}$、增量编译 $t\_{\text{compile}}$、浏览器模块替换 $t\_{\text{hmr}}$。

$$
t\_{\text{total}} = t\_{\text{fs}} + t\_{\text{compile}} + t\_{\text{hmr}}
$$

其中增量编译耗时与变更模块的依赖树深度 $d$ 线性相关：

$$
t\_{\text{compile}} \approx k \cdot d,\quad k \text{ 为单模块编译常量}
$$

通过合理拆分模块、减小依赖环，可显著降低 $d$，从而提升 HMR 体验。
