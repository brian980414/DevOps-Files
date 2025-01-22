# Run a Docker Compose and a Kubernetes Service
This guide explains how to start an application using Docker Compose and another service using Kubernetes.

## 📋 Prerequisites
Ensure you have the following installed and configured on your system:

- [Docker](https://docs.docker.com/desktop/) and [Docker Compose](https://docs.docker.com/compose/install/)
- [Kubernetes](https://kubernetes.io/docs/tasks/tools/install-kubectl-macos/)
- [Minikube](https://minikube.sigs.k8s.io/docs/start/)
- Git (to clone the repository)

---

## 🚀 Docker Compose Steps

### 1. Clone the Repository
Clone the repository to your local machine and navigate to the project directory:
```bash
git clone https://github.com/brian980414/DevOps-Files.git
cd DevOps-Files
```

### 2. Build and Execute the Service
Build and start the services defined in the `docker-compose.yml` file:
```bash
docker-compose up --build -d
```

### 3. Access the Service
Open your browser and go to:
- URL: `http://localhost:8000`
- **Credentials:**
  - Username: `brestrepo`
  - Password: `Bri1233*`

### 4. Stop the Service
To stop the services and remove the containers, run:
```bash
docker-compose down
```

---

## 🚀 Kubernetes Steps

### 1. Set Up the Environment
Start your Kubernetes environment using Minikube:
```bash
minikube start
```

### 2. Deploy the Service
Apply the Kubernetes manifest to deploy the service:
```bash
kubectl apply -f kubernetes.yaml
```

### 3. Expose the Service
Expose the backend service to access it externally:
```bash
minikube service backend-service --url
```

### 4. Stop the Service
Stop the Minikube environment:
```bash
minikube stop
```

---

## ❓ Need Help?
If you encounter any issues, feel free to contact me at: **+57 301 519 1221**