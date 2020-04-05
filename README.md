# Project 3 - Refactor Udagram app into Microservices and Deploy

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

The project is split into four parts:
1. [The Simple Frontend] udacity-c3-frontend - For Ionic client web application, which consumes the RestAPI Backend
2. [The RestAPI Feed Backend] udacity-c3-restapi-feed - For "feed" microservice
3. [The RestAPI User Backend] udacity-c3-restapi-user - For "user" microservice
4. [The Reverse Proxy] udacity-c3-deployment/docker - For running the Nginx as a reverse-proxy server

**The code and screenshots are available on github:
https://github.com/Guihosse/udcdndpjt3.git

**The docker images have been pushed to docker hub:
https://hub.docker.com/repository/docker/guihosse/udacity-restapi-feed
https://hub.docker.com/repository/docker/guihosse/udacity-restapi-user
https://hub.docker.com/repository/docker/guihosse/udacity-frontend
https://hub.docker.com/repository/docker/guihosse/reverseproxy

## clone the project from github

## create kubernete infrastructure

## configure configmap and secrets

## deploy the application using deployment files

## connect the deployment with service

## expose the application locally



