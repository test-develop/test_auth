FROM php:7.4.3-apache

RUN apt-get update && apt-get -y install -y libapache2-mod-auth-openidc  \
    vim

COPY ./auth_openidc.conf /etc/apache2/mods-available/auth_openidc.conf

RUN mkdir /var/www/html/secure

COPY ./secure/test.php /var/www/html/secure/test.php