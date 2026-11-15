# Dockerized Web Hosting Environment

## Project Overview

This project demonstrates how to host a static website
using Nginx inside a Docker container on Ubuntu Server.

## Technologies Used

- Ubuntu Server
- Docker Engine
- Docker Compose
- Nginx
- HTML
- CSS
- Git
- GitHub

## Project Structure

- compose.yaml - Docker configuration
- site/ - Website files
- backups/ - Website backups
- README.md - Project documentation

## Deployment

Start the web server:

docker compose up -d

Check the container:

docker compose ps

Access the website:

http://localhost:8080

## Stop the Web Server

docker compose stop
