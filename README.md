In this DevOps task, you need to build and deploy a full-stack CRUD application using the MEAN stack (MongoDB, Express, Angular 15, and Node.js). The backend will be developed with Node.js and Express to provide REST APIs, connecting to a MongoDB database. The frontend will be an Angular application utilizing HTTPClient for communication.  

The application will manage a collection of tutorials, where each tutorial includes an ID, title, description, and published status. Users will be able to create, retrieve, update, and delete tutorials. Additionally, a search box will allow users to find tutorials by title.

# MEAN Stack Full-Stack CRUD Application with CI/CD and Docker

This project demonstrates a **Full-Stack CRUD Application** built using the **MEAN Stack**:

- MongoDB
- Express.js
- Angular 15
- Node.js

The application is containerized using Docker and deployed automatically using GitHub Actions CI/CD pipeline with an Nginx reverse proxy.


---

# Technologies Used

## Backend
- Node.js
- Express.js
- MongoDB
- REST API

## Frontend
- Angular 15
- HTTPClient
- TypeScript

## DevOps Tools

- Docker
- Docker Compose
- GitHub Actions
- Nginx Reverse Proxy
- AWS EC2

- 
---

# CI/CD Pipeline

GitHub Actions is used for Continuous Integration and Continuous Deployment.

Pipeline Steps:

1. Pull code from GitHub
2. Build Docker images
3. Push images to DockerHub
4. Deploy containers on EC2
5. Restart containers automatically

---


GitHub Actions will:

- Build Images
- Push Images
- Deploy Application

---

# Features

- Full Stack CRUD Application
- REST API Integration
- Angular Frontend
- Node.js Backend
- MongoDB Database
- Docker Containerization
- Docker Compose Setup
- GitHub Actions CI/CD
- Nginx Reverse Proxy
- AWS Deployment

---

# Clean Up Containers

Stop containers:


# Deployment Steps

## Step 1: Clone Repository


git clone https://github.com/your-username/mean-devops-project.git


---

## Step 2: Move to Project Folder


cd mean-devops-project


---

## Step 3: Run Containers


docker-compose up -d


---

## Install Docker


sudo yum update -y
sudo yum install docker -y
sudo systemctl start docker
sudo systemctl enable docker
sudo usermod -aG docker ubuntu


---


# Project Structure


---


## Project setup

### Node.js Server

cd backend

npm install

You can update the MongoDB credentials by modifying the `db.config.js` file located in `app/config/`.

Run `node server.js`

### Angular Client

cd frontend

npm install

Run `ng serve --port 8081`

You can modify the `src/app/services/tutorial.service.ts` file to adjust how the frontend interacts with the backend.

Navigate to `http://localhost:8081/`
