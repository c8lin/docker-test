#base image
FROM centos:centos7

RUN yum install -y httpd 

EXPOSE 1024

ENTRYPOINT ["/usr/sbin/httpd"]
# CMD ["/usr/bin/echo 'hello_world'"]
