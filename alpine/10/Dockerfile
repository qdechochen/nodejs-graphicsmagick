FROM node:14-alpine
LABEL maintainer="Echo Chen<qdechochen@gmail.com>"
ENV TIMEZONE UCT
RUN set -ex; \
    apk add -U tzdata; \
    apk --update add graphicsmagick; \
    rm -rf /var/cache/apk/*
