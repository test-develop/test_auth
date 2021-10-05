FROM nginx

ARG VERSION=v5.1.1
ARG FILENAME=oauth2_proxy-${VERSION}.linux-amd64.go1.14.2

RUN apt-get update && apt-get install -y wget \
    vim

COPY ./server.conf /etc/nginx/conf.d/server.conf
