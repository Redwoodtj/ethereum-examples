FROM ubuntu:xenial-20210416
MAINTAINER Provable "info@provable.xyz"
RUN apt-get update && \
    apt-get install -y \
      curl \
      jq
COPY script.sh . 
ENTRYPOINT ["./script.sh"]
