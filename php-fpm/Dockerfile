FROM php:7-fpm

RUN pecl install xdebug-2.8.1 \
        && docker-php-ext-enable xdebug \
        && docker-php-ext-install mysqli pdo pdo_mysql && docker-php-ext-enable mysqli pdo_mysql