# Use Ubuntu base image
FROM ubuntu:22.04

# Update the package list
RUN apt-get update

# Install OpenJDK 8
RUN apt-get install -y openjdk-8-jdk

# Set JAVA_HOME environment variable
ENV JAVA_HOME /usr/lib/jvm/java-8-openjdk-amd64

# Add Java binaries to PATH
ENV PATH $JAVA_HOME/bin:$PATH

# Verify installation
RUN java -version
