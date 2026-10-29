FROM ubuntu:26.04@sha256:0e73b71479e7bc5f006bca872e25c3cd680dc052a0116f90d63ae363537db0dd

RUN mkdir -p /install/bin
ADD install/bin /install/bin

ENTRYPOINT /install/bin/translate
