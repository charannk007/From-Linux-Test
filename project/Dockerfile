FROM ubuntu:latest
RUN apt update
RUN apt install apache2 -y
COPY ./web/ /var/www/html/
EXPOSE 80
CMD ["apachectl", "-D", "FOREGROUND"]
