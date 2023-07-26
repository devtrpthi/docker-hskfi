FROM ubuntu:20.04

WORKDIR /usr/src/app

RUN \
  apt-get update && \
  apt-get -y install curl

COPY search.sh .

RUN chmod +x search.sh

CMD  ./search.sh 


