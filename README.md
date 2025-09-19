# Kubernetes Labs 🚀
<h3>Hands-on labs and experiments to learn, practice, and master Kubernetes.
This repository contains YAML manifests, exercises, and notes covering core Kubernetes concepts, from basic deployments to advanced workloads.</h3>

## 🛠️ Prerequisites

Before running the labs, ensure you have:

- Docker
 installed

- kubectl
 installed

- Minikube
 or a Kubernetes cluster (kind, k3s, or cloud provider)

- Basic knowledge of YAML and containerization

### Check Installation
```bash
kubectl version --client
minikube version
```
### Start First Cluster
```bash
minikube start
kubectl get nodes
kubectl cluster-info

```

### Basic Commands Namespace
```bash
minikube start
kubectl get nodes
kubectl cluster-info
```
### Pods
```bash
minikube start
kubectl get nodes
kubectl cluster-info
```

### Helpful Shortcuts
```bash
kubectl get all
kubectl describe <resource> <name>
kubectl explain pod

```