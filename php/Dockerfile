FROM php:8.2-fpm

# Install the mysqli (and pdo_mysql) extensions
RUN docker-php-ext-install mysqli pdo pdo_mysql

RUN apt-get update && apt-get install -y git

