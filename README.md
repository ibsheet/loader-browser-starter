# ibsheet-loader-browser-starter

[`@ibsheet/loader`](https://github.com/ibsheet/loader) starter for browser

## Clone Project

```bash
git clone https://github.com/ibsheet/loader-browser-starter ibl-browser-starter
cd ibl-browser-starter
```

## Copy IBSheet Library

copy to: `web/vendors/ibsheet`

## Start

### Using node with http-server

Guide: <https://github.com/http-party/http-server>

```bash
http-server ./web
```

### Using docker with nginx

Guide: <https://hub.docker.com/_/nginx>

* webroot: `./web`
* port: `8080`

#### docker run

```bash
docker run -p 8080:80 -v $(pwd)/web:/usr/share/nginx/html nginx
```

#### docker-compose

```bash
docker-compose up
```
