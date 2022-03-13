## docker chromium 自动生成仓库

[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/xiecat/alpine-chromium/Publish%20Releases%20to%20Hub)](https://github.com/xiecat/alpine-chromium/actions)
使用 `github action` 生成 docker 镜像并且自动推送给 `DockerHub`

latest 是最近一次更新版本   
nightly 当天版本   
yyyy-mm-dd 某天更新的版本   

## 每日最新版

每天自动构建

### 基础镜像

| 版本                                                 | 镜像大小                                                                                                                                                                     |
|:--------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| `docker pull becivells/alpine-chromium:latest`     | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/alpine-chromium/latest)](https://hub.docker.com/r/becivells/alpine-chromium/tags)         |
| `docker pull becivells/alpine-chromium-py3:latest` | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/alpine-chromium-py3/latest)](https://hub.docker.com/r/becivells/alpine-chromium-py3/tags) |
| `docker pull becivells/gobase-1.5:latest`          | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/gobase-1.5/latest)](https://hub.docker.com/r/becivells/gobase-1.5/tags)                   |
| `docker pull becivells/gobase-1.6:latest`          | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/gobase-1.6/latest)](https://hub.docker.com/r/becivells/gobase-1.6/tags)                   |
| `docker pull becivells/gobase-1.7:latest`          | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/gobase-1.7/latest)](https://hub.docker.com/r/becivells/gobase-1.7/tags)                   |

### 应用镜像

| 版本                                        | 镜像大小                                                                                                                                                   |
|:-----------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------:|
| `docker pull becivells/anew:latest`       | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/anew/latest)](https://hub.docker.com/r/becivells/anew/tags)             |
| `docker pull becivells/chaos:latest`      | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/chaos/latest)](https://hub.docker.com/r/becivells/chaos/tags)           |
| `docker pull becivells/dismap:latest`     | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/dismap/latest)](https://hub.docker.com/r/becivells/dismap/tags)         |
| `docker pull becivells/fofax:latest`      | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/fofax/latest)](https://hub.docker.com/r/becivells/fofax/tags)           |
| `docker pull becivells/interactsh:latest` | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/interactsh/latest)](https://hub.docker.com/r/becivells/interactsh/tags) |
| `docker pull becivells/nabbu:latest`      | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/nabbu/latest)](https://hub.docker.com/r/becivells/nabbu/tags)           |
| `docker pull becivells/nuclei:latest`     | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/nuclei/latest)](https://hub.docker.com/r/becivells/nuclei/tags)         |
| `docker pull becivells/sec-custom:latest` | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/sec-custom/latest)](https://hub.docker.com/r/becivells/sec-custom/tags) |
| `docker pull becivells/xray:latest`       | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/xray/latest)](https://hub.docker.com/r/becivells/xray/tags)             |
| `docker pull becivells/amass:latest`      | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/amass/latest)](https://hub.docker.com/r/becivells/amass/tags)           |
| `docker pull becivells/crawlergo:latest`  | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/crawlergo/latest)](https://hub.docker.com/r/becivells/crawlergo/tags)   |
| `docker pull becivells/dnsx:latest`       | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/dnsx/latest)](https://hub.docker.com/r/becivells/dnsx/tags)             |
| `docker pull becivells/httpx:latest`      | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/httpx/latest)](https://hub.docker.com/r/becivells/httpx/tags)           |
| `docker pull becivells/ksubdomain:latest` | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/ksubdomain/latest)](https://hub.docker.com/r/becivells/ksubdomain/tags) |
| `docker pull becivells/notify:latest`     | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/notify/latest)](https://hub.docker.com/r/becivells/notify/tags)         |
| `docker pull becivells/proxify:latest`    | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/proxify/latest)](https://hub.docker.com/r/becivells/proxify/tags)       |
| `docker pull becivells/subfinder:latest`  | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/subfinder/latest)](https://hub.docker.com/r/becivells/subfinder/tags)   |
