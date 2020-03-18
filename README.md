# entware-base

#### [entware-x64-base](https://hub.docker.com/r/forumi0721/entware-x64-base/)
![Docker Image Version (tag latest semver)](https://img.shields.io/docker/v/forumi0721/entware-x64-base/latest)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/forumi0721/entware-x64-base/latest)
![MicroBadger Layers (tag)](https://img.shields.io/microbadger/layers/forumi0721/entware-x64-base/latest)
![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721/entware-x64-base)
![Docker Stars](https://img.shields.io/docker/stars/forumi0721/entware-x64-base)
#### [entware-aarch64-base](https://hub.docker.com/r/forumi0721/entware-aarch64-base/)
![Docker Image Version (tag latest semver)](https://img.shields.io/docker/v/forumi0721/entware-aarch64-base/latest)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/forumi0721/entware-aarch64-base/latest)
![MicroBadger Layers (tag)](https://img.shields.io/microbadger/layers/forumi0721/entware-aarch64-base/latest)
![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721/entware-aarch64-base)
![Docker Stars](https://img.shields.io/docker/stars/forumi0721/entware-aarch64-base)
#### [entware-armhf-base](https://hub.docker.com/r/forumi0721/entware-armhf-base/)
![Docker Image Version (tag latest semver)](https://img.shields.io/docker/v/forumi0721/entware-armhf-base/latest)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/forumi0721/entware-armhf-base/latest)
![MicroBadger Layers (tag)](https://img.shields.io/microbadger/layers/forumi0721/entware-armhf-base/latest)
![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721/entware-armhf-base)
![Docker Stars](https://img.shields.io/docker/stars/forumi0721/entware-armhf-base)



----------------------------------------
#### Description

* Distribution : [Entware](https://github.com/Entware/Entware/)
* Architecture : x64,aarch64,armhf
* Appplication : -



----------------------------------------
#### Run

```sh
docker run -i -t --rm \
           forumi0721/entware-[ARCH]-base:latest
```



----------------------------------------
#### Usage

```dockerfile
FROM forumi0721/entware-[ARCH]-base:latest

#For cross compile on dockerhub (aarch64,armhf)
RUN ["docker-build-start"]

RUN 'build-code'

#For cross compile on dockerhub  (aarch64,armhf)
RUN ["docker-build-end"]
```



----------------------------------------
#### Docker Options

| Option             | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Ports

| Port               | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Volumes

| Volume             | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Environment Variables

| ENV                | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |

