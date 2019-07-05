FROM node:10-alpine
LABEL maintainer="Echo Chen<qdechochen@gmail.com>"
RUN set -ex; \
    if [ $TIMEZONE ]; then \
    apk add -U tzdata; \
    cp /usr/share/zoneinfo/$TIMEZONE /etc/localtime; \
    apk del tzdata; \
    fi \
RUN apk --update add graphicsmagick && \
    rm -rf /var/cache/apk/*


