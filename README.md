# WHATWEB

[![dockeri.co](https://dockeri.co/image/alexandreoda/whatweb)](https://hub.docker.com/r/alexandreoda/whatweb)


## INDEX

- [Badges](#BADGES)
- [Introduction](#INTRODUCTION)
- [Prerequis](#PREREQUIS)
- [Installation](#INSTALLATION)
- [Utilisation](#UTILISATION)
- [License](#LICENSE)


## BADGES

[![version](https://images.microbadger.com/badges/version/alexandreoda/whatweb.svg)](https://microbadger.com/images/alexandreoda/whatweb)
[![size](https://images.microbadger.com/badges/image/alexandreoda/whatweb.svg)](https://microbadger.com/images/alexandreoda/whatweb")
[![build](https://img.shields.io/docker/build/alexandreoda/whatweb.svg)](https://hub.docker.com/r/alexandreoda/whatweb)
[![automated](https://img.shields.io/docker/automated/alexandreoda/whatweb.svg)](https://hub.docker.com/r/alexandreoda/whatweb)


## INTRODUCTION

Ce repository contient le fichier Dockerfile de

- [whatweb](https://www.whatweb.net/)

Mis à jour automatiquement dans le [docker hub public](https://hub.docker.com/r/alexandreoda/whatweb)


## PREREQUIS

Installer [docker](https://www.docker.com)


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
