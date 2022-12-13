FROM php:8.1-apache-bullseye
WORKDIR /usr/src/myapp
COPY . /var/www/html/
RUN docker-php-ext-install pdo pdo_mysql
