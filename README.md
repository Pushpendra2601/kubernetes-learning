# kubernetes-learning
# 🚀 Kubernetes Learning Project

This repository contains my hands-on practice with Kubernetes, covering cluster setup, application deployment, and DevOps integration.

---

## 📁 Project Structure

```
kubernetes-files/
├── kind-cluster/        # Kind cluster configuration
├── nginx/               # Kubernetes manifests for Nginx app
│   ├── deployment.yml
│   ├── pod.yml
│   ├── namespace.yml
└── .gitignore
```

---

## ⚙️ Technologies Used

* Kubernetes
* Docker
* Kind (Kubernetes in Docker)
* kubectl
* Nginx

---

## 🧠 What I Learned

* Creating Kubernetes clusters using Kind
* Writing YAML manifests for:

  * Pods
  * Deployments
  * Namespaces
* Managing resources using `kubectl`
* Understanding Kubernetes architecture basics

---

## 🚀 How to Run This Project

### 1. Create Kind Cluster

```
kind create cluster --config kind-cluster/config.yml
```

---

### 2. Apply Kubernetes Manifests

```
kubectl apply -f nginx/
```

---

### 3. Verify Resources

```
kubectl get pods
kubectl get deployments
```

---

### 4. Delete Resources

```
kubectl delete -f nginx/
```

---

## 🔐 .gitignore

Sensitive and unnecessary files are ignored:

* `.kube/`
* `.docker/`
* `.aws/`
* `.azure/`
* `*.log`
* `*.swp`

---

## 📌 Future Improvements

* Add Service & Ingress
* Integrate CI/CD with Jenkins
* Deploy on cloud (AKS / EKS)
* Add Helm charts

---

## 👨‍💻 Author

**Pushpendra Vishwakarma**

---

## ⭐ Notes

This repository is part of my DevOps learning journey. Contributions, suggestions, and feedback are welcome!

