# entware-base
![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721/entware-base)
![Docker Stars](https://img.shields.io/docker/stars/forumi0721/entware-base)



----------------------------------------
### x64
![Docker Image Version](https://img.shields.io/docker/v/forumi0721/entware-base/latest)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/forumi0721/entware-base/latest)
### aarch64
![Docker Image Version](https://img.shields.io/docker/v/forumi0721/entware-base/aarch64)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/forumi0721/entware-base/aarch64)



----------------------------------------
#### Description

* Distribution : [Entware](https://github.com/Entware/Entware/)
* Architecture : x64,aarch64
* Appplication : -



----------------------------------------
#### Run

```sh
docker run -i -t --rm \
           forumi0721/entware-base:[ARCH_TAG]
```



----------------------------------------
#### Usage

```dockerfile
FROM forumi0721/entware-base:[ARCH_TAG]

#For cross compile on dockerhub (aarch64)
RUN ["docker-build-start"]

RUN 'build-code'

#For cross compile on dockerhub  (aarch64)
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

