## Dockerfile
#$ cat Dockerfile
#FROM ubuntu
#MAINTAINER name taegeun

#RUN apt update
#RUN apt install -y nginx

#EXPOSE 80
#EXPOSE 443


## build
user@DESKTOP-S33351E MINGW64 /c/test (master)
$ docker build --tag  tageunkim/nginx .
Sending build context to Docker daemon  63.49kB
Step 1/6 : FROM ubuntu
 ---> 74435f89ab78
Step 2/6 : MAINTAINER name taegeun
 ---> Using cache
 ---> 57b39d23cbbe
Step 3/6 : RUN apt update
 ---> Using cache
 ---> 70384c64eb3e
Step 4/6 : RUN apt install -y nginx
 ---> Using cache
 ---> 36a3c2bdd710
Step 5/6 : EXPOSE 80
 ---> Using cache
 ---> ab14bfbd82ac
Step 6/6 : EXPOSE 443
 ---> Using cache
 ---> 16e4e809301f
Successfully built 16e4e809301f
Successfully tagged tageunkim/nginx:latest
SECURITY WARNING: You are building a Docker image from Windows against a non-Windows Docker host. All files and directories added to build context will have '-rwxr-xr-x' permissions. It is recommended to double check and reset permissions for sensitive files and directories.

## docker file
https://hub.docker.com/repository/docker/tageunkim/nginx
