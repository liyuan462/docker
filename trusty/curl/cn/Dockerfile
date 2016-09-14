FROM liyuan462/ubuntu:trusty-curl

RUN cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
RUN curl http://mirrors.163.com/.help/sources.list.trusty > /etc/apt/sources.list
RUN apt-get update
