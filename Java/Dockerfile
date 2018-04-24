#Download the base ubuntu image
FROM ubuntu
#Install Java
RUN add-apt-repository -y ppa:webupd8team/java && \
apt-get update -y && \
apt-get install oracle-java8-installer && \
rm -rf /var/lib/apt/lists/* && \
rm -rf /var/cache/oracle-jdk8-installer


WORKDIR /data

ENV JAVA_HOME /usr/lib/jvm/java-8-oracle

CMD["bash"]
