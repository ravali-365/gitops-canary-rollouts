# GitOps Canary Deployments with Argo CD & Argo Rollouts

This project demonstrates **production-grade GitOps-based Canary Deployments** on Kubernetes using **Argo CD** and **Argo Rollouts**.  
It showcases progressive delivery, traffic shifting, automated sync, and rollback using Git as the single source of truth.

This project is designed to reflect **4–6 years of DevOps / SRE experience** and is suitable for **interviews and Global Talent Visa evidence**.

---

## 🧱 Architecture Overview

GitHub (Source of Truth)
↓  
Argo CD (GitOps Controller)  
↓  
Argo Rollouts (Progressive Delivery)  
↓  
Kubernetes (Minikube)  
↓  
NGINX Ingress (Traffic Routing)

---

## 🚀 Key Features

- GitOps-driven deployments using **Argo CD**
- **Canary deployments** using Argo Rollouts
- Progressive traffic shifting (10% → 50% → 100%)
- Separate **dev** and **prod** environments
- Automated sync, prune, and self-heal
- Manual rollback support
- Kubernetes-native implementation (no external CI dependency)

---

## 🛠️ Tech Stack

- Kubernetes (Minikube)
- Argo CD
- Argo Rollouts
- NGINX Ingress Contr

