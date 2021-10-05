FROM nginx

RUN apt-get update && apt-get install -y wget \
    vim

COPY ./server.conf /etc/nginx/conf.d/server.conf
