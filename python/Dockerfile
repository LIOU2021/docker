ARG VERSION=3.8

FROM python:${VERSION}-alpine

RUN apk update && apk upgrade && \
    apk add --no-cache bash git openssh vim libxml2-dev libxslt-dev

WORKDIR /var/www