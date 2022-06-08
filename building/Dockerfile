FROM ubuntu:18.04
RUN apt update
RUN apt install -y maven git
RUN https://github.com/boxfuse/boxfuse-sample-java-war-hello.git
RUN mvn -f ./boxfuse-sample-java-war-hello/pom.xml package