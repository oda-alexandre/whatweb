# WHATWEB

## INDEX

- [Badges](#BADGES)
- [Introduction](#INTRODUCTION)
- [Prerequisites](#PREREQUISITESITES)
- [Install](#INSTALL)
- [Use](#USE)
- [License](#LICENSE)

## BADGES

[![pipeline status](https://gitlab.com/oda-alexandre/whatweb/badges/master/pipeline.svg)](https://gitlab.com/oda-alexandre/whatweb/commits/master)

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

For scann a site copy/paste  in  a terminal

```sudo service tor start && sudo service privoxy start && whatweb --proxy 127.0.0.1:8118 http://lesite.com```

## LICENSE

[![GPLv3+](http://gplv3.fsf.org/gplv3-127x51.png)](https://gitlab.com/oda-alexandre/whatweb/blob/master/LICENSE)
