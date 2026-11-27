FROM docker.io/library/composer:2@sha256:5b2137f112f939a92788ceb5e55f54859d9dbf467a44037cf7760bdda949f365

RUN pecl bundle -d /usr/src/php/ext apcu \
 && docker-php-ext-install apcu