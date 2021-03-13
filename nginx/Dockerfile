FROM fpm-alpine

LABEL maintainer="Yuri Henrique <yurih567@gmail.com>"

RUN apk add --no-cache \
    bash \
    nginx \
    && mkdir -p /run/nginx \
    && rm -f  /etc/nginx/sites-enabled/default \
    && rm -f  /var/www/html/index.nginx-debian.html \
    && rm -rf  /var/www/localhost \
    && rm -rf /var/cache/apk/*
