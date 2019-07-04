FROM jenkins/jenkins:lts

# if we want to install via apt
USER root
RUN apt-get update
RUN apt-get install -y maven
RUN JAVA_OPTS="-Xmx500m -Xms500m"

