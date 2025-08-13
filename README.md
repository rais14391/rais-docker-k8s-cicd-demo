# Docker Kubernetes CI/CD Demo

This repository demonstrates a basic workflow for containerizing a Python app with Docker, deploying it to Kubernetes, and automating builds/tests using GitHub Actions CI/CD.

## Components
- Docker: Build and run containers
- Kubernetes: Deploy containers
- GitHub Actions: Automate build and test

## Structure
- `app.py`: Sample Python app
- `Dockerfile`: Container build instructions
- `k8s/`: Kubernetes deployment and service files
- `.github/workflows/ci-cd.yml`: CI/CD workflow
