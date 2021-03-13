# PHP Base Image with Nginx
Imagem base com php-fpm e nginx.

## Build

Criar imagem
```sh
docker build -t yurih567/php:7.4.15-nginx nginx
```

Roda o shell na imagem criada
```sh
docker run -it --rm yurih567/php:7.4.15-nginx /bin/bash
```

## Release

Envia imagem para o hub.docker
```sh
docker push yurih567/php:7.4.15-nginx
```
