# My Full Stack Docker App

## DevOps Setup

This project uses Docker Compose to run a frontend, backend, and Nginx reverse proxy.

### Services

- frontend: React/Vite frontend
- backend: API backend
- nginx: Reverse proxy exposed on port 80

### Run Locally

Run this from the root of the repository:

docker compose up --build -d

### URLs

Frontend:
http://localhost

Backend API:
http://localhost/api/ping

### CI/CD Pipeline

GitHub Actions automatically builds and pushes Docker images on every push to the main branch.
