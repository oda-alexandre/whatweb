# WHATWEB

![whatweb](https://raw.githubusercontent.com/oda-alexandre/whatweb/master/img/logo-whatweb.png) ![docker](https://raw.githubusercontent.com/oda-alexandre/whatweb/master/img/logo-docker.png)


## INDEX

- [Build Docker](#BUILD)
- [Introduction](#INTRODUCTION)
- [Prerequis](#PREREQUIS)
- [Installation](#INSTALLATION)
- [Utilisation](#UTILISATION)
- [License](#LICENSE)


## BUILD DOCKER

[![whatweb docker build](https://img.shields.io/docker/build/alexandreoda/whatweb.svg)](https://hub.docker.com/r/alexandreoda/whatweb)


## INTRODUCTION

Ce repository contient le fichier Dockerfile de [whatweb](https://www.whatweb.net/) pour [Docker](https://www.docker.com), mis à jour automatiquement dans le [Docker Hub](https://hub.docker.com/r/alexandreoda/whatweb/) public.


## PREREQUIS

Installer [Docker](https://www.docker.com)


## INSTALLATION

```
docker run -ti --rm --name whatweb -v ${HOME}:/home/whatweb alexandreoda/whatweb
```


## UTILISATION

Pour scanner un site copier/coller dans un terminal

```
sudo service tor start && sudo service privoxy start && whatweb --proxy 127.0.0.1:8118 http://lesite.com
```

## LICENSE

[![GPLv3+](http://gplv3.fsf.org/gplv3-127x51.png)](https://github.com/oda-alexandre/whatweb/blob/master/LICENSE)
