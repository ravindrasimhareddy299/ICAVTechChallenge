FROM centos
MAINTAINER ravigopireddy51
RUN yum install httpd -y
ADD index.html /var/www/html/index.html
CMD ["/usr/sbin/httpd","-D","FOREGROUND"]
EXPOSE 80
