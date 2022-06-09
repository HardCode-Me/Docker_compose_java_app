FROM java:8
FROM maven:alpine

RUN apt-get update
RUN apt-get install git -y

WORKDIR /tmp
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello

WORKDIR boxfuse-sample-java-war-hello
RUN mvn package
