FROM ubuntu:latest
LABEL maintainer "BSKY <me@bsky.moe>"

RUN apt-get update && apt-get install --no-install-recommends -y \
  zstd \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*

CMD [ "zstd" ]
