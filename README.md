# Kubernetes Task
This repository creates a deployment for the yanivomc/spring-music:latest image 

## Requirements: 
1) Docker desktop with kubernetes plugin
2) nginx ingress controller

#clone the project using the following command:
```
git clone https://github.com/ShadiFursa/K8S-Task.git
```

## Deployment: 
```
kubectl apply -f k8s-hw.yml
```
### Checking pods:
```
kubectl get pods
```
### checking service:
```
kubectl get svc
```
## Run ingress file:
```
kubectl apply -f ingress.yml
```
### You can access the spring music Service using URL: http://localhost/music 

