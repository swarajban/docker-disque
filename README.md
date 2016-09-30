# docker-disque

[![](https://images.microbadger.com/badges/image/swarajban/docker-disque.svg)](https://microbadger.com/images/swarajban/docker-disque "Get your own image badge on microbadger.com")

Dockerfile for [disque](https://github.com/antirez/disque). It is based on the comment from this [GitHub issue in the disque repo](https://github.com/antirez/disque/issues/160).

[On Docker Hub](https://hub.docker.com/r/swarajban/docker-disque/)

## Install
```
docker pull swarajban/docker-disque
```


## Usage
```
docker run --name my-disque -d -p 7711:7711  swarajban/docker-disque
```
