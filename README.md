# Kubernetes + NodeJS

bare metal template with mongodb, expressjs + kubernetes pre-configured

## Install kubernetes
go to https://k8s.io and install minikube + kubectl


## How to

Clone repo
```
git clone https://anddddrew/k8s-nodejs.git
```
Start minikube service
```
minikube start
```

Apply configuration
```
kubectl apply -f kubernetes/deployment.yl
```

Check pods
```
kubectl get pods
```

Get service
```
kubectl get svc
```

Start service
```
minikube service k8s-template
```
