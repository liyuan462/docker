FROM liyuan462/ubuntu:trusty-cn

RUN curl -sSf https://static.rust-lang.org/rustup.sh | sh

RUN apt-get update && apt-get install -y --no-install-recommends \
  gcc \
  && rm -rf /var/lib/apt/lists/*

WORKDIR /project
