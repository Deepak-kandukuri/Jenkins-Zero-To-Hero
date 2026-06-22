FROM jenkins/inbound-agent:latest

USER root

RUN apt-get update && apt-get install -y \
    openjdk-21-jdk \
    maven \
    docker.io \
    git

USER jenkins
