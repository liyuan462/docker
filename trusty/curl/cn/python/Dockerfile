FROM liyuan462/ubuntu:trusty-cn

RUN apt-get update && apt-get install -y --no-install-recommends \
  build-essential \
  libssl-dev \
  libffi-dev \
  python-dev \
  && rm -rf /var/lib/apt/lists/*

RUN curl https://bootstrap.pypa.io/get-pip.py | python
RUN mkdir /root/.pip && \
    curl https://raw.githubusercontent.com/liyuan462/docker-ubuntu/master/trusty/curl/cn/python/_files/pip.conf > /root/.pip/pip.conf

