FROM docker.io/library/composer:2@sha256:50ea4d33fdcde1adb0f045547295faa1548b33872e5f789dae5b02ce2fb5de93

RUN pecl bundle -d /usr/src/php/ext apcu \
 && docker-php-ext-install apcu