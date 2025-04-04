FROM ubuntu:22.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && \
    apt-get install -y software-properties-common && \
    add-apt-repository --yes --update ppa:ansible/ansible && \
    apt-get install -y ansible vim openssh-client && \
    apt-get clean
