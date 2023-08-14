FROM ubuntu:20.04


ENV TZ=Asia/Dubai
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

RUN apt update
RUN apt install -y tzdata

RUN apt-get install -y zip unzip
RUN apt-get install -y \
        php \
        php-cgi \
        php-cli \
        php-common \
        php-curl \
        php-dev \
        php-json \
        php-mbstring \
        php-mysql \
        php-odbc \
        php-phpdbg \
        php-sqlite3 \
        php7.4-fpm

EXPOSE  9000
