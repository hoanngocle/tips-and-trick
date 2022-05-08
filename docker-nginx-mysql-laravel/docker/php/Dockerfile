FROM php:8.1-fpm-alpine

# Extension zip for laravel & mysql driver for mysql
RUN docker-php-ext-install pdo pdo_mysql

# Install composer
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer
