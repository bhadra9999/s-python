# this is my web container
  From centos:6.9
  MAINTAINER bhadra<bhadra@localhost>  
  RUN yum install -y httpd
  COPY index.html /var/www/html
  ENTRYPOINT /usr/sbin/httpd -D FOREGROUND
