
# Docker varnish

```
docker pull igloo/varnish
```

## Features

- [varnish-modules](https://github.com/varnish/varnish-modules)

## Usage

```sh
docker run -d -p 8080:80 \
  -v path/default.vcl:/usr/local/etc/varnish/default.vcl \
  igloo/varnish
```
