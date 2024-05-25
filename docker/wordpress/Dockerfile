FROM wordpress:latest

RUN apt-get update && apt-get install -y \
    autoconf \
    g++ \
    make \
    libbz2-dev \
    libreadline-dev \
    libssl-dev \
    libxml2-dev \
    libxslt1-dev \
    zlib1g-dev

RUN pecl install xdebug && docker-php-ext-enable xdebug

COPY php/php.ini /usr/local/etc/php/conf.d/php.ini