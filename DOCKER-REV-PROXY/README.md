
DevOps Intern Assignment: Nginx Reverse Proxy + Docker Compose

This project demonstrates a simple Docker-based microservice architecture with Nginx acting as a reverse proxy for two backend services:

- Service 1 A Golang application
- Service 2 A Python application

Nginx handles routing to each service based on the URL path prefix.

---

 Project Structure
devops-intern-assignment/
├── docker-compose.yml
├── nginx/
│   ├── nginx.conf
│   └── Dockerfile
├── service_1/   # Golang app
│   ├── Dockerfile
│   └── [source files...]
├── service_2/   # Python app
│   ├── Dockerfile
│   └── [source files...]
└── README.m

