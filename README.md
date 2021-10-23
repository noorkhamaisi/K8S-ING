## Kubernetes Task

Welcome to my repository that creates a deployment for the yanivomc/spring-music:latest image . 

## Your Needs 
1. Docker desktop with kubernetes plugin .
2. nginx ingress controller

Clonning the project using the command : 
https://github.com/noorkhamaisi/K8S-ING.git


## Deployment

kubectl apply -f K8S-ING.yaml

## Getting The Service 
kubectl get svc

## Getting The Pods 
kubectl get pods

## Running Ingress

kubectl apply -f Ingress.yaml

You can visit the spring music Service using URL: http://localhost/music





## Noor Khamaisi