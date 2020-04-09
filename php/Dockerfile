FROM php:7.2-fpm
RUN docker-php-ext-install pdo_mysql \
&& docker-php-ext-install mbstring \
&& docker-php-ext-install bcmath \
&& pecl install redis \
&& docker-php-ext-enable redis
