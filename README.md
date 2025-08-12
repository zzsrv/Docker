# [Docker](https://github.com/zzsrv/Docker)

Docker常用镜像仓库(每日更新到最新版镜像)。

Github: <https://github.com/zzsrv/Docker>

## 支持镜像及镜像版本

每日上午 8 点 Pull Docker 常用镜像仓库，Pull 完成后将同时 Push 到阿里云镜像仓库 (杭州) 。

阿里云个人镜像限制300个仓库，理论上应该能满足常用需求，使用时可以Fork项目自己修改，也可以直接通过如下地址使用。

### Docker 镜像地址
#### 阿里云镜像仓库地址 (杭州)：registry.cn-hangzhou.aliyuncs.com

|  源镜像  |        加速镜像        |
| :-------------: | :------------------------: |
|  zzsrv/openwrt:latest  | zzsrv/openwrt:latest |
|  nextcloud:latest  | zzsrv/nextcloud:latest |
|  linuxserver/heimdall:latest  | zzsrv/heimdall:latest |
|  p3terx/aria2-pro:latest  | zzsrv/aria2-pro:latest |
|  jeessy/ddns-go:latest  | zzsrv/ddns-go:latest |
|  filebrowser/filebrowser:latest  | zzsrv/filebrowser:latest |
|  deluan/navidrome:latest  | zzsrv/navidrome:latest |
|  jc21/nginx-proxy-manager:latest  | zzsrv/nginx-proxy-manager:latest |
|  linuxserver/transmission:latest  | zzsrv/transmission:latest |
|  ghcr.io/immich-app/immich-server:release  | zzsrv/immich-server:release |
|  ghcr.io/immich-app/immich-machine-learning:release  | zzsrv/immich-machine-learning:release |
|  redis:latest  | zzsrv/redis:latest |
|  redis:6.2-alpine  | zzsrv/redis:6.2-alpine |
|  tensorchord/pgvecto-rs:pg14-v0.2.0  | zzsrv/pgvecto-rs:pg14-v0.2.0 |
|  whyour/qinglong:latest  | zzsrv/qinglong:latest |
|  jxxghp/moviepilot:latest  | zzsrv/moviepilot:latest |
|  iyuucn/iyuuplus-dev:latest  | zzsrv/iyuuplus-dev:latest |
|  iyuucn/iyuuplus:latest  | zzsrv/iyuuplus:latest |
|  <del>lovechen/embyserver:latest</del>  | <del>zzsrv/embyserver:latest</del> |
|  amilys/embyserver:latest  | zzsrv/embyserver:latest-amilys |
|  gdy666/lucky:latest  | zzsrv/lucky:latest |
|  xhofe/alist:latest  | zzsrv/alist:latest |
|  zhayujie/chatgpt-on-wechat:latest  | zzsrv/chatgpt-on-wechat:latest |
|  cloudnas/clouddrive2-unstable:latest  | zzsrv/clouddrive2-unstable:latest |
|  dreamacro/clash:latest  | zzsrv/clash:latest |
|  neosmemo/memos:latest  | zzsrv/memos:latest |
|  mzz2017/v2raya:latest  | zzsrv/v2raya:latest |
|  snowdreamtech/frpc:latest  | zzsrv/frpc:latest |
|  mnbf9rca/cups-google-print:latest  | zzsrv/cups-google-print:latest |
|  gitlab/gitlab-ce:latest  | zzsrv/gitlab-ce:latest |
|  jenkins/jenkins:latest  | zzsrv/jenkins:latest |
|  xianwei2022/stars.client:latest  | zzsrv/stars.client:latest |
|  nastool/nas-tools:latest  | zzsrv/nas-tools:latest |
|  linyuan0213/nas-tools:latest  | zzsrv/nas-tools:latest-linyuan0213 |
|  linyuan0213/nas-tools:3.5.6  | zzsrv/nas-tools:latest-linyuan0213-3.5.6 |
|  hsuyelin/nas-tools:latest  | zzsrv/nas-tools:latest-hsuyelin |
|  linuxserver/plex:latest  | zzsrv/plex:latest |
|  haishanh/yacd:latest  | zzsrv/yacd:latest |
|  talebook/talebook:latest  | zzsrv/talebook:latest |
|  chishin/nginx-proxy-manager-zh:latest  | zzsrv/nginx-proxy-manager-zh:latest |
|  joyqi/typecho:nightly-php8.2-apache  | zzsrv/typecho:nightly-php8.2-apache |
|  neilpang/acme.sh:latest  | zzsrv/acme.sh:latest |
|  linuxserver/qbittorrent:latest  | zzsrv/qbittorrent:latest |
|  nevinee/qbittorrent:latest  | zzsrv/qbittorrent:latest-nevinee |
|  alpine:latest  | zzsrv/alpine:latest |
|  mysql:latest  | zzsrv/mysql:latest |
|  zmister/mrdoc:v9.3  | zzsrv/mrdoc:v9.3 |
|  ddsderek/wxchat:latest  | zzsrv/wxchat:latest |
|  postgres:latest  | zzsrv/postgres:latest |
|  postgres:16  | zzsrv/postgres:16 |
|  joplin/server:latest  | zzsrv/server:latest-joplin |
|  hausen1012/squoosh:latest  | zzsrv/squoosh:latest |
|  corentinth/it-tools:latest  | zzsrv/it-tools:latest |
|  frooodle/s-pdf:latest  | zzsrv/s-pdf:latest |
|  frooodle/s-pdf:latest-fat  | zzsrv/s-pdf:latest-fat |
|  nattertool/natter:latest  | zzsrv/natter:latest |
|  nyanmisaka/jellyfin:latest  | zzsrv/jellyfin:latest-nyanmisaka |
|  xhongc/music_tag_web:latest  | zzsrv/music_tag_web:latest |
|  homeassistant/home-assistant:latest  | zzsrv/home-assistant:latest |
|  tinymediamanager/tinymediamanager:latest  | zzsrv/tinymediamanager:latest |
|  certbot/certbot:latest  | zzsrv/certbot:latest |
|  youshandefeiyang/allinone:latest  | zzsrv/allinone:latest |
|  ollama/ollama:latest  | zzsrv/ollama:latest |
|  docker.gitea.com/gitea:latest  | zzsrv/gitea:latest |
|  待补充 | 待补充 |


## 加速镜像使用方法

直接 Pull 阿里云镜像仓库地址 + 加速镜像
```
docker pull registry.cn-hangzhou.aliyuncs.com/zzsrv/nextcloud:latest
docker pull registry.cn-hangzhou.aliyuncs.com/zzsrv/heimdall:latest
```
