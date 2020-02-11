## SANE Backend (with libusb1.0) build environment (Debian) Dockerfile


### Base Docker Image

* [aoqi/debian-mips64el](https://hub.docker.com/r/aoqi/debian-mips64el)

### Build

```
$ docker build --rm -t "oingo/docker-sane-backend-debian-mips64el" .
```

### Installation

1. Install [Docker](https://www.docker.com/).

2. Download : `docker pull oingo/docker-sane-backend-debian-mips64el`


### Usage

    docker run -it -v <sane-backend-volume>:/root/project oingo/docker-sane-backend-debian-mips64el /bin/bash
