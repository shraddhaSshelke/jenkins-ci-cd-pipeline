# Jenkins CI/CD Pipeline

This project demonstrates a simple CI/CD pipeline using Jenkins to build, test, and deploy a sample Python app using a Docker container.

##  Tools Used
- Jenkins
- Docker
- Python (Simple HTTP Server)
- GitHub

##  Pipeline Stages
1. Clone repository
2. Build step
3. Run unit tests (mocked)
4. Deploy the container

##  Run Locally
```bash
docker build -t jenkins-demo-app .
docker run -p 8000:8000 jenkins-demo-app
