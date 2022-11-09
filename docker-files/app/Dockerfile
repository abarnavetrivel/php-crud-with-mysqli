FROM php:7.2-apache
LABEL "Author" = "Abarna"
RUN apt-get update && apt-get install -y

RUN docker-php-ext-install mysqli pdo_mysql
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
COPY src/ /var/www/html/

