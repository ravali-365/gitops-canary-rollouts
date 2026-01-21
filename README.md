# gitops-canary-rollouts
Build a multi-environment GitOps setup (dev + prod) using Argo CD and Argo Rollouts with canary deployments and rollback.

## Step 1 - Cluster Add-ons
### Commands
```bash
minikube addons enable ingress
kubectl get pods -n ingress-nginx

kubectl create namespace argo-rollouts || true
kubectl apply -n argo-rollouts -f https://raw.githubusercontent.com/argoproj/argo-rollouts/stable/manifests/install.yaml
kubectl get pods -n argo-rollouts

brew install kubectl-argo-rollouts
kubectl argo rollouts version
