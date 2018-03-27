# dockerfile-swoole-composer

## This a docker images based by php:cli-alpine

The image contains:
1. The common php extensions, such as `mbstring` `mysqli` `pdo_mysql` `openssl`
2. The latest version phpredis extension
3. The latest version swoole extension and build by `--enable-coroutine --enable-async-redis --enable-mysqlnd`
4. php composer, you can use it build project quicky.

## This is just a runtime environment.

All image is only `73.5MB`


---

此镜像是基于 php:cli-alpine 构建，其镜像内包含如下：

1. 常用的php扩展，比如`mysqli` `pdo_mysql` `mbstring` `openssl`等
2. 最新版本的phpredis扩展
3. 最新版本的swoole扩展，并且开启了`协程` `异步Redis支持` `mysqlnd支持`
4. 最新的composer，可以快速构建项目

## 此镜像仅为运行环境
此镜像最终缩减到仅为`73.5MB`