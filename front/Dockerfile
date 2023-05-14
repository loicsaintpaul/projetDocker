FROM node:16.19.1

MAINTAINER Loic SP <contact@lsaintpaul-dev.com>

EXPOSE 4200

WORKDIR /usr/app

RUN git clone https://github.com/realraec/quizgame-frontend.git .
RUN git pull && git checkout main
