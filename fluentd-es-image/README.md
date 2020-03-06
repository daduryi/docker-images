# fork
git@github.com:kubernetes/kubernetes.git
cluster/addons/fluentd-elasticsearch/fluentd-es-image/

# version
fluentd 1.8.0
PREFIX = daduryi/fluentd_elasticsearch/fluentd:v2.9.0

# 使用Makefile构建

https://www.cnblogs.com/woshimrf/p/make-docker.html

- Makefile是什么
- Makefile基本语法
- Docker构建用的指令

```
# 构建一个版本的镜像
make build

# 构建完毕，运行一下镜像，看看内容是否正确(本文件中没有start命令)
make start  

# 最后推送到docker仓库
make push
```