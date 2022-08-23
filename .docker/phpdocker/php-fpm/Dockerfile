FROM phpdockerio/php:8.1-fpm
WORKDIR "/var/www/app"

RUN apt-get update; \
    apt-get -y --no-install-recommends install \
        php8.1-amqp \ 
        php8.1-http \ 
        php8.1-raphf \
        php8.1-memcache \
        php8.1-memcached \ 
        php8.1-oauth \ 
        php8.1-pgsql \ 
        php8.1-phpdbg \
        php8.1-redis \ 
        php8.1-xdebug \ 
        php8.1-xmlrpc \ 
        php8.1-yaml; \
    apt-get clean; \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*
