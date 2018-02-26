FROM php:7-fpm-alpine3.7

# you migth need to set a proxy so that docker-php-ext-install can fetch dependencies
# ENV HTTP_PROXY "http://10.0.2.2:8888"
# ENV HTTPS_PROXY "https://10.0.2.2:8888"

# Add Necessary PHP Extensions
# https://github.com/docker-library/php/issues/279
RUN docker-php-ext-install mysqli
