# WHATWEB

![logo](https://assets.gitlab-static.net/uploads/-/system/project/avatar/12904487/unnamed.png)

- [WHATWEB](#whatweb)
  - [INDEX](#index)
  - [BADGES](#badges)
  - [INTRODUCTION](#introduction)
  - [PREREQUISITES](#prerequisites)
  - [INSTALL](#install)
    - [DOCKER RUN](#docker-run)
    - [DOCKER COMPOSE](#docker-compose)
  - [LICENSE](#license)

## BADGES

[![pipeline status](https://gitlab.com/oda-alexandre/whatweb/badges/master/pipeline.svg)](https://gitlab.com/oda-alexandre/whatweb/commits/master)

## INTRODUCTION

Docker image of :

- [whatweb](https://www.whatweb.net/)

Continuous integration on :

- [gitlab pipelines](https://gitlab.com/oda-alexandre/whatweb/pipelines)

Automatically updated on :

- [docker hub public](https://hub.docker.com/r/alexandreoda/whatweb)

## PREREQUISITES

Use [docker](https://www.docker.com)

## BUILD

### DOCKER RUN

```\
docker run -ti --rm \
--name whatweb \
-v ${HOME}:/home/whatweb \
alexandreoda/whatweb
```

### DOCKER COMPOSE

```yml
version: "2.0"

services:
  whatweb:
    container_name: whatweb
    image: alexandreoda/whatweb
    restart: "no"
    privileged: false
    volumes:
      - "${HOME}:/home/whatweb"
```

## LICENSE

[![GPLv3+](http://gplv3.fsf.org/gplv3-127x51.png)](https://gitlab.com/oda-alexandre/whatweb/blob/master/LICENSE)
