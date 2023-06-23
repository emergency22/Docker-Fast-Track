FROM centos:latest
RUN yum -y install httpd
ADD webserver.tar.gz /var/www/html/
CMD ["-D", "FOREGROUND"]
ENTRYPOINT [ "/usr/sbin/httpd" ]
EXPOSE 80

#I couldn't get this to build :/