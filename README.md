# CRUD MEAN Application Deployment

## Project Overview
This is a full-stack MEAN (MongoDB, Express, Angular, Node.js) CRUD application.  
The project is containerized using Docker, deployed with Docker Compose, and automated via Jenkins CI/CD pipeline.  
Nginx is configured as a reverse proxy to serve the application on port 80.

---

## Prerequisites
- Ubuntu VM (AWS EC2)
- Docker & Docker Compose installed
- Jenkins installed and running
- GitHub repository with application code
- DockerHub account for storing images

---

## Setup & Deployment Instructions

### 1. Clone Repository
```bash
git clone https://github.com/aditipandey18/crud-mean-app.git
cd crud-mean-app/meanapp
