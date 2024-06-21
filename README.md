# [Docker](https://github.com/zzsrv/Docker)

Docker常用镜像仓库(每日更新到最新版镜像)。

Github: <https://github.com/zzsrv/Docker>

## 支持镜像及镜像版本

每日上午 8 点 Pull Docker 常用镜像仓库，Pull 完成后将同时 Push 到阿里云镜像仓库 (杭州) 。

阿里云个人镜像限制300个仓库，理论上应该能满足上常用需求，使用时可以Fork项目自己修改，也可以提PR丰富仓库镜像后，直接通过如下地址使用。

### Docker 镜像地址

|  支持镜像  |                  阿里云镜像仓库 (杭州)                  |
| :-------------: | :-----------------------------------------------------: |
|  nextcloud:latest  | registry.cn-hangzhou.aliyuncs.com/zzsrv/nextcloud:latest |
|  linuxserver/heimdall:latest  | registry.cn-hangzhou.aliyuncs.com/zzsrv/heimdall:latest |
|  p3terx/aria2-pro:latest  | registry.cn-hangzhou.aliyuncs.com/zzsrv/aria2-pro:latest |
|  jeessy/ddns-go:latest  | registry.cn-hangzhou.aliyuncs.com/zzsrv/ddns-go:latest |
|  filebrowser/filebrowser:latest  | registry.cn-hangzhou.aliyuncs.com/zzsrv/filebrowser:latest |
|  deluan/navidrome:latest  | registry.cn-hangzhou.aliyuncs.com/zzsrv/navidrome:latest |
|  jc21/nginx-proxy-manager:latest  | registry.cn-hangzhou.aliyuncs.com/zzsrv/nginx-proxy-manager:latest |
|  linuxserver/transmission:latest  | registry.cn-hangzhou.aliyuncs.com/zzsrv/transmission:latest |
|  ghcr.io/immich-app/immich-server:release  | registry.cn-hangzhou.aliyuncs.com/zzsrv/immich-server:latest |
|  ghcr.io/immich-app/immich-machine-learning:release  | registry.cn-hangzhou.aliyuncs.com/zzsrv/immich-machine-learning:latest |
|  redis:6.2-alpine  | registry.cn-hangzhou.aliyuncs.com/zzsrv/redis:6.2-alpine |
|  tensorchord/pgvecto-rs:pg14-v0.2.0  | registry.cn-hangzhou.aliyuncs.com/zzsrv/pgvecto-rs:pg14-v0.2.0 |
|  whyour/qinglong:latest  | registry.cn-hangzhou.aliyuncs.com/zzsrv/qinglong:latest |
|  jxxghp/moviepilot:latest  | registry.cn-hangzhou.aliyuncs.com/zzsrv/moviepilot:latest |
|  iyuucn/iyuuplus-dev:latest  | registry.cn-hangzhou.aliyuncs.com/zzsrv/iyuuplus-dev:latest |
|  待补充 | 待补充 |


## 镜像使用方法

1、先 Pull 阿里云镜像仓库的镜像，Pull时只需要原镜像最后一个“/”后的内容，然后再加上仓库地址“registry.cn-hangzhou.aliyuncs.com/zzsrv/”

docker pull registry.cn-hangzhou.aliyuncs.com/zzsrv/nextcloud:latest

docker pull registry.cn-hangzhou.aliyuncs.com/zzsrv/heimdall:latest

docker pull registry.cn-hangzhou.aliyuncs.com/zzsrv/aria2-pro:latest

docker pull registry.cn-hangzhou.aliyuncs.com/zzsrv/ddns-go:latest

2、原脚本不用做修改，原镜像地址可以直接使用（原理类似文件MD5，秒传等，上面已经把文件 Pull 下来了）

docker pull nextcloud:latest

docker pull linuxserver/heimdall:latest

docker pull p3terx/aria2-pro:latest

docker pull jeessy/ddns-go:latest

