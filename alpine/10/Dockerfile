FROM node:10-alpine
LABEL maintainer="Echo Chen<qdechochen@gmail.com>"
ENV TIMEZONE UCT
RUN set -ex; \
    apk add -U tzdata; \
    cp /usr/share/zoneinfo/$TIMEZONE /etc/localtime; \
    apk del tzdata; \
    apk --update add graphicsmagick; \
    rm -rf /var/cache/apk/*


