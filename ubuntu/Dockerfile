FROM ubuntu:18.04

RUN apt update \
    && apt install -qy less man rsync vim-tiny strace curl wget htop iputils-ping net-tools nmap

ENV HOME=/home/dev
RUN useradd --create-home --home-dir $HOME dev && chown -R dev:dev $HOME

USER dev
WORKDIR /home/dev

CMD bash
