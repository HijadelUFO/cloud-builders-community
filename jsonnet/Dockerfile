FROM ubuntu:xenial-20210416

RUN \
    apt update -y && \
    apt -y install build-essential git && \
    git clone https://github.com/google/jsonnet.git && \
    cd jsonnet && \
    make && \
    ./jsonnet --help

ENTRYPOINT ["/jsonnet/jsonnet"]
