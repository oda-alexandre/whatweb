# WHATWEB

![logo](https://assets.gitlab-static.net/uploads/-/system/project/avatar/12904487/unnamed.png)

## INDEX

- [WHATWEB](#whatweb)
  - [INDEX](#index)
  - [BADGES](#badges)
  - [FIRST UPDATE](#first-update)
  - [INTRODUCTION](#introduction)
  - [PREREQUISITES](#prerequisites)
  - [INSTALL](#install)
  - [LICENSE](#license)

## BADGES

[![pipeline status](https://gitlab.com/oda-alexandre/whatweb/badges/master/pipeline.svg)](https://gitlab.com/oda-alexandre/whatweb/commits/master)

## FIRST UPDATE

Date: 01-01-01

## INTRODUCTION

Docker image of :

- [whatweb](https://www.whatweb.net/)

Continuous integration on :

- [gitlab](https://gitlab.com/oda-alexandre/whatweb/pipelines)

Automatically updated on :

- [docker hub public](https://hub.docker.com/r/alexandreoda/whatweb)

## PREREQUISITES

Use [docker](https://www.docker.com)

## INSTALL

```docker run -ti --rm --name whatweb -v ${HOME}:/home/whatweb alexandreoda/whatweb```

## USE

For scann a site copy/paste in a terminal

```sudo service tor start && sudo service privoxy start && whatweb --proxy 127.0.0.1:8118 http://siteweb.com```

## LICENSE

[![GPLv3+](http://gplv3.fsf.org/gplv3-127x51.png)](https://gitlab.com/oda-alexandre/whatweb/blob/master/LICENSE)
