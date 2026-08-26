# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent




## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

````
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
````

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service
```



基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler



* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

````
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
````

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service
```



基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler



* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

````
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
````

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service
```



基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler



* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

````
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
````

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service
```



基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler



* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

````
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
````

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service
```



基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler



* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

````
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
````

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service
```



基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler



* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

````
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
````

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service
```



基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler



* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

````
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
````

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service
```



基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler



* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

````
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
````

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service
```



基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler



* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

````
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
````

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service
```



基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler



* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

````
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
````

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service
```



基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler



* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

````
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
````

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service
```



基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler



* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

````
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
````

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service
```



基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler



* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

````
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
````

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service
```



基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler



* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

````
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
````

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service
```



基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler



* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

````
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
````

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service
```



基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler



* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

````
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
````

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo# Euler Thrift Service
```



基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler



* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── bootstrap.sh       # 启动脚本
├── requirements.txt   # Python 依赖
├── logging_config.py  # 日志配置
└── idls/              # Thrift IDL 生成代码
```

## 常见问题

### ConnectionRefusedError: \[Errno 61] Connection refused

如果在 macOS 系统中进行开发，访问远端服务（数据库、下游服务）时需要通过 consul 进行服务发现，但 macOS 上没有公司内的服务发现系统，因此连接会失败。

这时可以设置 `CONSUL_HTTP_HOST` 环境变量来指定使用远端的 consul 做服务发现。例如：

```sh
$ export CONSUL_HTTP_HOST=10.6.131.78
```

目前推荐使用 devbox 上的 consul 为本地开发环境提供服务发现功能。

## 更多

* <br />

# Euler Thrift Service

基于字节跳动 Euler 框架的 Thrift 服务示例。

## 项目简介

本项目是一个使用 Python +  框架构建的 Thrift 服务，提供 `ExampleService` 服务。

* 服务框架: Euler

* 通信协议: Thrift

* 监听地址: `tcp://[::]:1234`

* 并发模型: gevent

## 本地开发

### 创建虚拟环境

```sh
$ python3 -m venv venv
```

### 激活虚拟环境

```sh
$ source venv/bin/activate
```

如果你使用 VSCode 或 PyCharm 等 IDE 进行开发，需要在选择解释器（Interpreter）时选择 `venv/bin/python`，否则代码补全和跳转功能会不正常。

### 安装依赖

首先参考 <https://python.byted.org/pip-setup.html> 设置 pip 私有源，如果已经设置过则可以跳过此步。

```sh
$ pip install -r requirements.txt
```

### 启动项目

```sh
$ ./bootstrap.sh
```

或者直接执行：

```sh
$ python server.py
```

## 项目结构

```
.
├── server.py          # 服务入口
├── client.py          # 客户端示例
├── boo
```

