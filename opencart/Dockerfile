FROM oberd/php-8.0-apache:latest

RUN apt-get update -y && apt-get install -y libpng-dev

RUN apt-get update && apt-get install -y zlib1g-dev 

RUN apt-get update && apt-get install -y mariadb-client

RUN docker-php-ext-install gd
