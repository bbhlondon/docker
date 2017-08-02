FROM node:8.2.1-alpine

RUN apt-get update; apt-get upgrade -y; apt-get dist-upgrade -y; apt-get autoremove -y; apt-get autoclean -y
RUN apt-get install -y awscli

CMD [node]
