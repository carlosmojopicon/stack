FROM php:7.3.2-fpm-alpine3.9

RUN apk add --update \
  postgresql-dev \
  && docker-php-ext-install pdo pdo_pgsql
