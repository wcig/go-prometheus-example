# prometheus go 示例

## 1.介绍

prometheus go 示例, 包括以下组件:

* goapp
* node_exporter
* prometheus
* grafana


## 2.快速开始

执行命令:

```shell
docker-compose up -d
```

如果遇到 docker image 拉取慢问题, 可以配置如下镜像加速:

```json
{
  "registry-mirrors": [
    "https://docker.mirrors.ustc.edu.cn",
    "http://hub-mirror.c.163.com",
    "https://registry.docker-cn.com"
  ]
}
```
