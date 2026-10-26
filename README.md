<<'EOF'
# DevOps Web Application

A containerized web application built with Flask, Gunicorn, Nginx, and Docker Compose.

## Architecture

- Flask — web application
- Gunicorn — WSGI application server
- Nginx — reverse proxy
- Docker Compose — container orchestration

## Features

- Multi-container architecture
- Internal Docker network
- Environment-based configuration
- Health endpoint
- Automatic container restart
- Nginx reverse proxy

## Requirements

- Docker
- Docker Compose

## Run

```bash
docker compose up -d --build
