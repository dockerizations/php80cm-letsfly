FROM laravelsail/php80-composer

RUN apt-get update -y && apt-get upgrade -y

RUN pecl install mongodb && docker-php-ext-enable mongodb

# RUN echo "extension=mongodb.so" >> /usr/local/etc/php/php.ini
