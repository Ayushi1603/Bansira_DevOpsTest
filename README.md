# Bansira_DevOpsTest
**Dockerization: Steps to Create a Docker Image**
This document will outline the steps that are necessary to create a Docker image for a Node.js **"Hello World"** application. The instructions below guide you through cloning the application repository, creating multi-stage Dockerfile, building the docker image and pushing it to DockerHub.
**Steps:**
Clone Node.js "Hello World" Application

Start off by cloning the Node.js "Hello World" application repository from GitHub: **git clone https://github.com/johnpapa/node-hello.git**

Navigate to the Application Directory: Navigate yourself to the cloned repository; 
cd node-hello

**Create Multi-Stage Dockerfile:** 
Go to specified directory and create multi-stage dockerfile.

**Build And Tag The Docker Image:**
Build docker image and tag- docker build -t ayushi0316/node_hello:latest .

Push The Docker Image To DockerHub. 
Ensure logging into your account before pushing an image with this command “docker login”
docker push ayushi0316/node_hello:latest

Your newly built, pushed, deployed, used in applications is now ready on ayushi0316/node_hello:latest.
