FROM ubuntu:latest
LABEL maintainer "PyContribs <pycontribs@googlegroups.com>"

ENV TZ=Europe/Zurich
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

RUN apt-get update -y && \
    apt-get install -y apt-utils gcc git python3 python3-dev python3-pip libssl-dev sudo init

ENV SHELL /bin/bash
