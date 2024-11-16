FROM ubuntu:latest

RUN apt-get update && \
     apt install -y nginx

COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
