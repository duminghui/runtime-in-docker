FROM golang:1.10.1-alpine3.7

RUN \
    echo "https://mirror.tuna.tsinghua.edu.cn/alpine/v3.7/main/" > /etc/apk/repositories && \
    apk update && \
    apk upgrade && \
    apk add -v bash bash-completion && \
    rm -rf /var/cache/apk/*

COPY bashrc /root/.bashrc
CMD 'bash'


