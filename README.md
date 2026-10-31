# DevOps Assignment 2: Build, Containerize and Automate

**Student Name:** Muhammad Ibraheem  
**Roll Number:** FA23-BAI-055  

## Overview
This repository contains a personal portfolio webpage built with HTML and CSS, containerized using Docker and Nginx, and automated via a GitHub Actions CI/CD pipeline.

## Running Locally with Docker
docker build -t ibraheem11/devops-a2:manual .
docker run -d -p 8080:80 --name page ibraheem11/devops-a2:manual
