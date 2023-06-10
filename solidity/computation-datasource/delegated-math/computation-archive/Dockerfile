FROM ubuntu:xenial-20210416
MAINTAINER Oraclize "info@oraclize.it"

RUN apt-get update && apt-get install bc
CMD echo $ARG0 + $ARG1 | /usr/bin/bc \
   && exit 0; 
