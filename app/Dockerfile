FROM node:21.6.1-alpine
ARG APP_WORKDIR
WORKDIR ${APP_WORKDIR}

ENV TZ Asia/Tokyo

RUN apk update
RUN apk upgrade
RUN apk add git vim