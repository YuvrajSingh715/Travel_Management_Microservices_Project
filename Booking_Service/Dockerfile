FROM ubuntu
RUN apt update -y
RUN apt install apache2 -y
COPY index.html /var/www/html
EXPOSE 81
CMD ["/usr/sbin/apachectl", "-D", "FOREGROUND"]
[root@Worker1 Travel_Management_Microservices_Project]#
