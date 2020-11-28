FROM openjdk:8-jre

MAINTAINER mariamarlu14@gmail.com

RUN mkdir -p /usr/local/app

WORKDIR /usr/local/app

COPY drop/*.jar /usr/local/app/

COPY drop/run.sh usr/local/app/run.sh

COPY drop/application.properties application.properties

EXPOSE 8080

ENTRYPOINT sh run.sh
