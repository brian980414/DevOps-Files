# Run a Docker Compose and a Kubernetes Service
This code give you the guide to start an App from Docker Compose and another service from Kubernetes

## 📋 Prerequisites
Make sure you have docker, docker compose, kubernetes and minikube.

- [Docker](https://docs.docker.com/desktop/) and [Docker Compose](https://docs.docker.com/compose/install/)
- [Kubernetes](https://kubernetes.io/docs/tasks/tools/install-kubectl-macos/)
- Git (To clone the repository)

## 🚀 Docker Compose Steps
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/brian980414/DevOps-Files.git
   cd DevOps-Files

### 2. Build and excecute the service
    ```bash
    docker-compose up --build -d

### 3. Go to the service.
Go to `http://localhost:8000`
user: brestrepo
pass: Bri1233*

### 4. Stop the service.
Para detener los servicios y eliminar los contenedores, ejecuta:
```bash
docker-compose down

### 1. Set up the enviroment.
```bash
minikube start

### 1. Set up the enviroment.
```bash
minikube start

### 2. Deploye the service
```bash
kubectl apply -f kubernetes.yaml

### 3. Expose the service
```bash
minikube service backend-service --url

### 3. Stop the service
```bash
minikube stop