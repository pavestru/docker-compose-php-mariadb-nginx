FROM php:fpm-alpine

RUN apk add zlib-dev
RUN docker-php-ext-install mysqli zip

CMD ["php-fpm"]

EXPOSE 9000
