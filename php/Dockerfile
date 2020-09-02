FROM php:7.2-fpm

RUN apt update\
	&& apt -y install iputils-ping \
	&& docker-php-ext-install mysqli \
	&& docker-php-ext-install sockets