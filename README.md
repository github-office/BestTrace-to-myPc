# BestTrace-to-myPc
### ipip开发的路由追踪工具，用于检测VPS到自己电脑的路由情况。
### 版权归原作者所有，我只是搬运工。
### [IPIP官网](https://www.ipip.net/)

#### 使用方法
```bash
yum update
yum install -y epel-release
yum install uzip
mkdir besttrace && cd besttrace
wget https://github.com/github-office/BestTrace-to-myPc/releases/download/v1.3.2/besttrace4linux.zip
unzip besttrace4linux.zip && chmod +x *
./besttrace –q 1 IP地址
```

BestTrace 4 Linux/Mac/BSD

(C) 2015 - 2021, IPIP.NET. All Rights Reversed.

---- How To Use ----

本工具为 Go 语言编写，多个系统环境下预编译版本，只要赋予可执行权限，即可使用。

---- ChangeLog ----

1.3.2 (03/25/2021)
  1、修正主机名中有特殊字符导致签名失败的问题。

1.3.1 (03/12/2021)
  1、修正 IPv6 网络环境下 API 请求中签名错误的问题。

1.3 (06/15/2020)
  1、使用新版本 API 获取数据；
  2、修订细节。

1.2 (07/25/2018)
  1、初步支持 IPv6。

1.1.5 (05/23/2018)
  1、支持英文显示，会自动根据当前 LANG 环境变量进行判断，也可以通过命令行参数进行指定。

1.1.4 (07/05/2017)
  1、合并更改 API 地址，提升执行速度。

1.1.3 (01/17/2017)
  1、修复一个获取本地 HOSTNAME 时可能会崩溃的 bug。

1.1.2 (12/26/2016)
  1、为加快执行速度，支持批量异步发包模式。

1.1.1 (11/08/2016)
  1、在 OpenBSD 下编译测试通过。

1.1 (11/07/2016)
  1、参数顺序支持任意放置了；
  2、支持 MacOS 命令行。

1.0 (10/25/2016)
  1、第一个版本。
