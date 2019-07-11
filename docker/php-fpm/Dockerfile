FROM php:fpm-alpine

RUN apk add zlib-dev libzip-dev libpng libpng-dev
RUN docker-php-ext-configure zip --with-libzip
RUN docker-php-ext-install mysqli zip gd
RUN apk del libpng-dev zlib-dev

CMD ["php-fpm"]

EXPOSE 9000
