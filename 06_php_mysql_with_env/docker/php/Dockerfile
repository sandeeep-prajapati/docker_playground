FROM php:8.2-apache

RUN docker-php-ext-install pdo pdo_mysql mysqli
RUN echo "ServerName localhost" >> /etc/apache2/apache2.conf
RUN a2enmod rewrite
