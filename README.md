# docker-php-fpm-7.1
docker php 7.1 基本环境build以及搭建基本运行环境

`基本的php扩展 mongodb,redis,xdebug,apcu,bcmath 如需要自行修改安装`

# 1. 拉取镜像
 `git clone https://github.com/longfens/docker-php-7.1.git`

# 2. build 镜像 -t 
 `cd docker-php-7.1`
 
 `docker build -f Dockerfile.runtime -t zw0222/php:7.1.10 .`
# 3. 查看
 `docker images`
