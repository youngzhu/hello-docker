1. 离线加载镜像（使用已经下载下来的镜像文件）
```shell
docker load -i xxx.tar
```

2. environment 的两种方式
```yaml
# 方式一
environment:
  XX1_YY1: v1
  XX2_YY2: v2

# 方式二
environment:
  - "xx1.yy1=v1"
  - "xx2.yy2=v2"
```