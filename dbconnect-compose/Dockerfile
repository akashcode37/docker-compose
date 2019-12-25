FROM centos
RUN yum install httpd -y
COPY index.html /var/www/html/index.html
COPY py.cgi /var/www/cgi-bin/py.cgi
ENV MYSQL_HOST $MYSQL_HOST
EXPOSE 80
ENTRYPOINT httpd -DFOREGROUND
