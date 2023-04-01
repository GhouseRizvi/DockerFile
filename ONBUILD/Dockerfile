FROM almalinux
RUN yum install nginx -y
ONBUILD ADD simple.txt /tmp/
ONBUILD RUN yum update -y
