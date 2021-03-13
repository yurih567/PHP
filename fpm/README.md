# PHP FPM Image
Imagem base para criação de container.

## Build

Criar imagem base
```sh
docker build -t yurih567/php:7.4.15-fpm-alpine fpm
```

Roda o shell na imagem criada
```sh
docker run -it --rm yurih567/php:7.4.15-fpm-alpine /bin/sh
```

## Release

Envia imagem para o hub.docker
```sh
docker push yurih567/php:7.4.15-fpm-alpine
```
