FROM centos:centos7

RUN yum -y update && yum -y install epel-release && yum -y install nginx

COPY files/index.html /usr/share/nginx/html/

EXPOSE 22 80

CMD ["nginx", "-g", "daemon off;"]
