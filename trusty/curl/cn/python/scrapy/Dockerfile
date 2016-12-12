FROM liyuan462/ubuntu:trusty-py

RUN apt-get update && apt-get install -y --no-install-recommends \
  libxml2-dev \
  libxslt1-dev \
  && rm -rf /var/lib/apt/lists/*

RUN pip install scrapy

