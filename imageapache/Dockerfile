
FROM php:8.1-apache
COPY ./moduls/ /usr/local/apache2/htdocs/
COPY ./000-default.conf /etc/apache2/sites-available/000-default.conf
COPY ./ports.conf /etc/apache2/ports.conf

RUN chown -R www-data:www-data /var/www/html 

USER www-data:www-data

EXPOSE 8081 8084 8085