# OpenJDK 7 Dockerfile
#
# https://github.com/oscerd/docker-java

# Pull base image.
FROM phusion/baseimage:0.9.16
MAINTAINER Andrea Cosentino <ancosen1985@yahoo.com>

# Install Openjdk 7
RUN apt-get -y update
RUN apt-get install -y openjdk-7-jdk

RUN apt-get clean 
RUN rm -rf /var/lib/apt/lists/* 
RUN rm -rf /tmp/* 
RUN rm -rf /var/tmp/*

# Set environment variables
ENV JAVA_HOME /usr/lib/jvm/java-7-openjdk-amd64/
ENV PATH $JAVA_HOME/bin:$PATH

CMD ["/sbin/my_init"]
