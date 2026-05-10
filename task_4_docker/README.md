# Docker Web Server Project

## Overview
This project demonstrates how to deploy a static website using Docker and Nginx.

## What I built
- A simple HTML website
- A Docker image using Dockerfile
- A running container serving the website

## Project Structure
my-docker-app/
├── index.html
├── Dockerfile
└── README.md

## How to Run

### 1. Build image
docker build -t my-docker-web .

### 2. Run container
docker run -d -p 8080:80 my-docker-web

### 3. Open in browser
http://localhost:8080

## Docker Commands Used
docker ps
docker images
docker stop <container>
docker rm <container>

## Outcome
Successfully deployed a web server using Docker.
