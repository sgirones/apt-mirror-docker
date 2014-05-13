FROM ubuntu:trusty

MAINTAINER  Salvador Girones <salvadorgirones@gmail.com>

RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get -y install apt-mirror

ENTRYPOINT ['apt-mirror']
