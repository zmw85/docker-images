FROM ubuntu:18.04

# prevent tzdata interaction
ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y \
  curl \
  awscli

RUN curl -sL https://deb.nodesource.com/setup_10.x | bash -

RUN apt-get install -y \
  nodejs \
  && rm -rf /var/lib/apt/lists/*
