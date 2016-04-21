# About POCKEATMINE of Docker
# Version:0.14.0
FROM ubuntu:14.04
MAINTAINER Tianrking <tian.r.king@gmail.com>
RUN apt-get update -y && \
	apt-get install python-pip -y && \
        pip install shadowsocks
ENTRYPOINT ["/usr/local/bin/ssserver"]
