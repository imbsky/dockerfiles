FROM ubuntu:latest

RUN apt-get update && apt-get install --no-install-recommends -y \
  zstd \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*

CMD [ "zstd" ]
