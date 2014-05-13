FROM ubuntu

MAINTAINER  Salvador Girones <salvadorgirones@gmail.com>

RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get install apt-mirror

ENTRYPOINT ['apt-mirror']
