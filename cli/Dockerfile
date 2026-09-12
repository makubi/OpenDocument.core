FROM ubuntu:24.04@sha256:224a1869083a311ef3f13648a154ba79832fbef6364d31493642ca03082da254

RUN mkdir -p /install/bin
ADD install/bin /install/bin

ENTRYPOINT /install/bin/translate
