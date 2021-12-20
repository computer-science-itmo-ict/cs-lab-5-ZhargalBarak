FROM ubuntu:20.04

ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get -y update
RUN apt-get -y install apache2
COPY index.html /var/www/html/index.html
EXPOSE 80
CMD apache2ctl -D FOREGROUND
