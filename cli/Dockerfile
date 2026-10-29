FROM ubuntu:24.04@sha256:24737cef17f4e22b1977df7d9a05e77c4e28b7da5b8911f8d8ccda136bf3573c

RUN mkdir -p /install/bin
ADD install/bin /install/bin

ENTRYPOINT /install/bin/translate
