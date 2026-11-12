FROM docker.io/library/composer:2@sha256:ca11f643d7791ebdd90a34fc20caf11380d434007ae539a9ea75cd9212e13dca

RUN pecl bundle -d /usr/src/php/ext apcu \
 && docker-php-ext-install apcu