FROM bitrixdock/php56-fpm:latest

COPY ./php.ini /etc/php5/fpm/conf.d/90-php.ini
COPY ./php.ini /etc/php5/cli/conf.d/90-php.ini

RUN usermod -u 1000 www-data

WORKDIR "/var/www"

EXPOSE 9000
