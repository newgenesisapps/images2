FROM alpine

RUN apk update && apk add nginx

COPY files/index.html /usr/share/nginx/html/

EXPOSE 22 80

CMD ["nginx", "-g", "daemon off;"]
