
---

## 🧩 **Task 2 – Kubernetes Deployment**
📁 Repo name: **Kaiburr-Task2-Kubernetes**

```markdown
# Kaiburr Task 2 – Kubernetes Deployment

## 📌 Objective
Deploy the backend REST API to Kubernetes using a Deployment and Service.

---

## 🧱 Files Included
- `deployment.yaml` – Defines pod & replica set  
- `service.yaml` – Exposes backend via NodePort  
- `mongo-deployment.yaml` – MongoDB configuration  

---

## 🧰 Tech Stack
- Kubernetes  
- Docker  
- Spring Boot backend container  

---

## 🚀 Steps to Deploy
```bash
kubectl apply -f k8s/mongo-pv-pvc.yaml
kubectl apply -f k8s/mongo-deployment.yaml
kubectl apply -f k8s/app-deployment.yaml
