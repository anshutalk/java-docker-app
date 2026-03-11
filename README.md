# Java Docker Application

This project demonstrates how to containerize a Java application using Docker.

## Technologies Used

- Java
- Docker
- Alpine Linux

## Dockerfile Explanation

1. Pull OpenJDK base image
2. Create working directory
3. Copy Java source code
4. Compile using javac
5. Run the Java program

## Build Docker Image

docker build -t java-app .

## Run Container

docker run java-app
