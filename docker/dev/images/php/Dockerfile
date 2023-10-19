FROM php:8.1.25RC1-fpm-alpine3.18

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

ADD php.ini /usr/local/etc/php/conf.d/40-custom.ini

WORKDIR /usr/src/project/hello.dev

COPY ./project_docker/hello.dev /usr/src/project/hello.dev