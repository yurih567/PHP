# Composer Image for Development
Imagem base para desenvolver a aplicação php.

## Build

Criar imagem base
```sh
docker build -t yurih567/php:7.4.15-fpm-dev fpm-dev
```

Roda o shell na imagem criada
```sh
docker run -it --rm yurih567/php:7.4.15-fpm-dev /bin/sh
```

## Release

Envia imagem para o hub.docker
```sh
docker push yurih567/php:7.4.15-fpm-dev
```
