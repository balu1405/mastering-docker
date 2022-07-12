FROM centos:7

RUN yum update -y && yum install vim -y && yum install telnet -y 

WORKDIR script

COPY . script

CMD ["sh", "script/hello-world.sh"]
