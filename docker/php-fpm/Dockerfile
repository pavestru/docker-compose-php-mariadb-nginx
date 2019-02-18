FROM php:fpm-alpine

RUN apk add zlib-dev libpng libpng-dev
RUN docker-php-ext-install mysqli zip gd
RUN apk del libpng-dev

CMD ["php-fpm"]

EXPOSE 9000
