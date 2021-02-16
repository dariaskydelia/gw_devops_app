FROM ubuntu:latest
LABEL maintainer="KB"
RUN apt-get update -y && \
apt-get install -y openjdk-8-jdk
RUN mkdir java_project
WORKDIR /java_project
ADD app.jar /java_project/
CMD ["java", "-jar", "app.jar", "--server.port=8888"]
