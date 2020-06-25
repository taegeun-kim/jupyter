## Dockerfile##
$ cat Dockerfile
FROM ubuntu
MAINTAINER name taegeun

RUN apt update
RUN apt install -y nginx

EXPOSE 80
EXPOSE 443
