# SpringBoot Calculator DevOps Project

## Features
- Spring Boot JDK8 Calculator
- Azure DevOps Pipeline
- Docker Build & Push
- DEV2 Deployment
- PROD2 Deployment
- Self Hosted Agent

## Build
mvn clean package

## Run
docker build -t calculator .
docker run -p 8080:8080 calculator
