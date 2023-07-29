FROM php:7.4-fpm-alpine3.16

RUN apk add git curl zip
RUN docker-php-ext-install pdo mysqli pdo_mysql

COPY --from=composer:2 /usr/bin/composer /usr/bin/composer

COPY conf/* $PHP_INI_DIR/conf.d/
