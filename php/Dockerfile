FROM php:7.4.14-apache
COPY src/ /var/www/html && html/ /var/www
RUN docker-php-ext-install mysqli pdo pdo_mysql
RUN a2enmod userdir
RUN a2enmod rewrite
