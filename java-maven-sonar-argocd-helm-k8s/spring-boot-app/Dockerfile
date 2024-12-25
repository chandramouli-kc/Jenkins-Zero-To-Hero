# You can change this base image to anything else
# But make sure to use the correct version of Java
#FROM adoptopenjdk/openjdk11:alpine-jre

# Simply the artifact path
#ARG artifact=target/spring-boot-web.jar

#WORKDIR /opt/app
#CMD pwd

#COPY ${artifact} app.jar

# This should not be changed
#ENTRYPOINT ["java","-jar","app.jar"]
# Use the official Alpine Linux base image
FROM alpine:latest

# Set the working directory inside the container
WORKDIR /app

# Copy files from the host to the container (optional, if needed)
# COPY . /app

# Install essential tools or packages (optional, if needed)
RUN apk add --no-cache bash

# Default command to run when the container starts
CMD ["echo", "Hello from Alpine!"]
