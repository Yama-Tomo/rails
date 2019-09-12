FROM ruby:2.6.4-alpine

WORKDIR /app

RUN apk update && apk upgrade \
  && apk add --no-cache  git gcc make libc-dev sqlite sqlite-dev g++ postgresql-dev mysql-dev libxml2 libxml2-dev ncurses-dev tzdata

CMD sh