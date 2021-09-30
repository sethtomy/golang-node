FROM golang:1.16

RUN apt-get update
RUN apt -y upgrade

RUN apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates
RUN curl -sL https://deb.nodesource.com/setup_12.x

RUN apt -y install nodejs
