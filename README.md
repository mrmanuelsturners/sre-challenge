# Elixir Phoenix Application Deployment with Helm

This guide provides step-by-step instructions to deploy an Elixir Phoenix application and a PostgreSQL database using Helm in a Kubernetes cluster. It also includes troubleshooting steps and cleanup instructions.

---

## Prerequisites

1. **Kubernetes Cluster**: A running Kubernetes cluster (e.g., Minikube, Docker Desktop, or a cloud provider like AWS EKS, GKE, or AKS).
2. **Helm**: Helm must be installed. Follow the [official Helm installation guide](https://helm.sh/docs/intro/install/).
3. **kubectl**: The Kubernetes command-line tool must be installed and configured to connect to your cluster.

---

## Steps to Deploy

### 1. **Create a Namespace**
Create a namespace for the deployment:

```bash
kubectl create namespace stord
