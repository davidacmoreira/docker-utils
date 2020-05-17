FROM ubuntu:16.04

RUN apt-get update \
    && apt-get install -y curl bash git nano

# node
RUN curl -sL https://deb.nodesource.com/setup_12.x | bash - \
    && apt-get install -y nodejs