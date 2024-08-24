# Use an official Jenkins agent base image with JDK 11
FROM jenkins/agent:jdk11

# Install Docker CLI
USER root
RUN apt-get update && apt-get install -y docker.io

# Switch back to Jenkins user
USER jenkins
