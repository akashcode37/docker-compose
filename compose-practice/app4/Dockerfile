FROM centos
MAINTAINER akash
RUN yum install httpd -y
COPY data /var/www/html/
EXPOSE 80
ENTRYPOINT httpd -DFOREGROUND
