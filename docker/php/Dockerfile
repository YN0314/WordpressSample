FROM wordpress:5.7.2-fpm-alpine

ARG TZ

RUN apk --no-cache update && \
    apk --no-cache upgrade && \
    apk --no-cache add \
    tzdata \
    vim \
    git && \
    cp //usr/share/zoneinfo/${TZ} /etc/localtime
