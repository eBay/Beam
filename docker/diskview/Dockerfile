FROM ubuntu:16.04
RUN apt-get update && apt-get -y install \
    libbz2-1.0 \
    liblz4-1 \
    libsnappy1v5 \
    libssl1.0.0 \
    libzstd0 \
    zlib1g
LABEL description=akutan-diskview
ADD akutan-diskview akutan-diskview
EXPOSE 9980/tcp
ENTRYPOINT [ "/akutan-diskview" ]
CMD []
