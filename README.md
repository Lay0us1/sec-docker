## 常用安全工具自动生成仓库

[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/xiecat/sec-docker/Publish%20sec-custom%20to%20Hub)](https://github.com/xiecat/sec-docker/actions)
使用 `github action` 生成 docker 镜像并且自动推送给 `DockerHub`

**latest** 是最近一次更新版本   
**nightly** 当天版本   
**yyyy-mm-dd** 某天更新的版本   

## 国内加速构建
国内网络环境太差。为了好构建可以加入国内源测试。测试结束后移除即可

```shell
RUN sed -i 's/dl-cdn.alpinelinux.org/mirrors.tuna.tsinghua.edu.cn/g' /etc/apk/repositories
RUN pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
```
## 定期更新镜像

每天自动构建

### 基础镜像

| 版本                                                 | 镜像大小                                                                                                                                                                     |
|:--------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| `docker pull becivells/alpine-chromium:latest`     | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/alpine-chromium/latest)](https://hub.docker.com/r/becivells/alpine-chromium/tags)         |
| `docker pull becivells/alpine-chromium-py3:latest` | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/alpine-chromium-py3/latest)](https://hub.docker.com/r/becivells/alpine-chromium-py3/tags) |
| `docker pull becivells/gobase-1.5:latest`          | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/gobase-1.5/latest)](https://hub.docker.com/r/becivells/gobase-1.5/tags)                   |
| `docker pull becivells/gobase-1.6:latest`          | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/gobase-1.6/latest)](https://hub.docker.com/r/becivells/gobase-1.6/tags)                   |
| `docker pull becivells/gobase-1.7:latest`          | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/gobase-1.7/latest)](https://hub.docker.com/r/becivells/gobase-1.7/tags)                   |
| `docker pull becivells/alpine-gcc:latest`          | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/alpine-gcc/latest)](https://hub.docker.com/r/becivells/alpine-gcc/tags)                   |

### 应用镜像

|                    版本                     | 镜像大小                                                                                                                                                   |
|:-----------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------:|
|    `docker pull becivells/anew:latest`    | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/anew/latest)](https://hub.docker.com/r/becivells/anew/tags)             |
|    `docker pull becivells/nmap:latest`    | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/nmap/latest)](https://hub.docker.com/r/becivells/nmap/tags)             |
|    `docker pull becivells/zmap:latest`    | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/zmap/latest)](https://hub.docker.com/r/becivells/zmap/tags)             |
|   `docker pull becivells/chaos:latest`    | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/chaos/latest)](https://hub.docker.com/r/becivells/chaos/tags)           |
|   `docker pull becivells/dismap:latest`   | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/dismap/latest)](https://hub.docker.com/r/becivells/dismap/tags)         |
|   `docker pull becivells/fofax:latest`    | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/fofax/latest)](https://hub.docker.com/r/becivells/fofax/tags)           |
| `docker pull becivells/interactsh:latest` | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/interactsh/latest)](https://hub.docker.com/r/becivells/interactsh/tags) |
|   `docker pull becivells/nabbu:latest`    | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/nabbu/latest)](https://hub.docker.com/r/becivells/nabbu/tags)           |
|   `docker pull becivells/nuclei:latest`   | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/nuclei/latest)](https://hub.docker.com/r/becivells/nuclei/tags)         |
| `docker pull becivells/sec-custom:latest` | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/sec-custom/latest)](https://hub.docker.com/r/becivells/sec-custom/tags) |
|    `docker pull becivells/xray:latest`    | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/xray/latest)](https://hub.docker.com/r/becivells/xray/tags)             |
|   `docker pull becivells/amass:latest`    | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/amass/latest)](https://hub.docker.com/r/becivells/amass/tags)           |
| `docker pull becivells/crawlergo:latest`  | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/crawlergo/latest)](https://hub.docker.com/r/becivells/crawlergo/tags)   |
|    `docker pull becivells/dnsx:latest`    | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/dnsx/latest)](https://hub.docker.com/r/becivells/dnsx/tags)             |
|   `docker pull becivells/httpx:latest`    | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/httpx/latest)](https://hub.docker.com/r/becivells/httpx/tags)           |
| `docker pull becivells/ksubdomain:latest` | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/ksubdomain/latest)](https://hub.docker.com/r/becivells/ksubdomain/tags) |
|   `docker pull becivells/notify:latest`   | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/notify/latest)](https://hub.docker.com/r/becivells/notify/tags)         |
|  `docker pull becivells/proxify:latest`   | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/proxify/latest)](https://hub.docker.com/r/becivells/proxify/tags)       |
|  `docker pull becivells/massdns:latest`   | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/massdns/latest)](https://hub.docker.com/r/becivells/massdns/tags)       |
| `docker pull becivells/subfinder:latest`  | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/subfinder/latest)](https://hub.docker.com/r/becivells/subfinder/tags)   |
| `docker pull becivells/oneforall:latest`  | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/oneforall/latest)](https://hub.docker.com/r/becivells/oneforall/tags)   |
|  `docker pull becivells/masscan:latest`   | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/becivells/masscan/latest)](https://hub.docker.com/r/becivells/masscan/tags)   |
