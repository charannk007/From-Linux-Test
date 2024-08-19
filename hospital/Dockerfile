FROM ubuntu
RUN apt update
RUN apt install apache2 -y
COPY ./hospital /var/www/html/
EXPOSE 80
CMD ["apachectl","-D","FOREGROUND"]

