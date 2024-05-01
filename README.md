# Simple Microservices Project

## Description

The project consists of two simple services:
 - spring-boot-app - Java application with SpringBoot
 - node-app - Node.js application with Express

# We have to dependencies in order for this to work

- Docker
- Docker Compose

# Steps for running the app

1. Clone the repo

# bash

git clone https://github.com/zerinkr/basic-microservices.git
cd basic-microservices

2. Build the apps

docker-compose up --build


3. Check if the app is working properly with Health Check

bash <(curl -s https://raw.githubusercontent.com/kkenan/basic-microservices/master/health_check.sh)

if it's working properly you should see the output 

"All checks passed. Congrats!"

4. Stop the apps

docker-compose down