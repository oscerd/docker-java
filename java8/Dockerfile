# Java 8 Dockerfile
#
# https://github.com/oscerd/ubuntu

# Pull base image.
FROM phusion/baseimage:0.9.15
MAINTAINER Andrea Cosentino <ancosen1985@yahoo.com>

# Install Oracle Java 8
RUN echo oracle-java8-installer shared/accepted-oracle-license-v1-1 select true | debconf-set-selections
RUN add-apt-repository -y ppa:webupd8team/java
RUN apt-get update
RUN apt-get install -y oracle-java8-installer

RUN apt-get clean 
RUN rm -rf /var/lib/apt/lists/* 
RUN rm -rf /tmp/* 
run rm -rf /var/tmp/*

CMD ["/sbin/my_init"]
