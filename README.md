# OpenArkCompiler_docker
方舟编译器的docker环境一键搭建脚本

### 1，安装docker

### 2，下载方舟编译器docker镜像
docker pull dp543831577/ark:v1.0

### 3，查看镜像，找到ubuntu的镜像id
docker images

### 4，创建并启动容器
docker run -dit --name ARK 镜像id(上面看到的dp543831577/ark:v1.0的IMAGE ID) /bin/bash

### 5，创建并启动容器
docker exec -it ARK /bin/bash

### 6，初始化方舟编译器脚本
sh ./ark.sh
