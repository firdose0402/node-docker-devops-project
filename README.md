# Node.js Docker DevOps Project

This is a simple Node.js web application deployed using Docker on an EC2 Ubuntu server.

## Project Overview

This project demonstrates how a DevOps engineer can deploy a Node.js application using Docker containers on AWS EC2.

## Technologies Used

- Node.js
- Docker
- Ubuntu
- AWS EC2
- Git & GitHub

## Project Structure

node-docker-app
│
├── app.js
├── package.json
├── Dockerfile
└── README.md

## Application Code

The Node.js application runs a simple HTTP server on port 3000 and returns a basic HTML response.

## Docker Setup

Build Docker Image

docker build -t node-app .

Run Docker Container

docker run -d -p 3000:3000 node-app

## Access Application

Open in browser:

http://EC2-PUBLIC-IP:3000

## Example Output

Node.js App Running on Docker EC2

## DevOps Workflow

Developer → GitHub → Docker Build → AWS EC2 Deployment → User Access

## Author

DevOps Project Demo
