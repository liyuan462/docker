FROM liyuan462/ubuntu:trusty-curl

RUN cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
RUN curl http://mirrors.163.com/.help/sources.list.trusty > /etc/apt/sources.list
RUN apt-get update

# Set the locale
RUN locale-gen en_US.UTF-8  
ENV LANG en_US.UTF-8  
ENV LANGUAGE en_US:en  
ENV LC_ALL en_US.UTF-8
