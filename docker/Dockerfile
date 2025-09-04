FROM php:8.3-apache

# Enable mod_rewrite for .htaccess
RUN a2enmod rewrite

# Applies custom .htaccess
RUN sed -i 's/AllowOverride None/AllowOverride All/' /etc/apache2/apache2.conf

WORKDIR /var/www/html
