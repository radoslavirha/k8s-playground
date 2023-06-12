# Kubernetes playground

For https://www.udemy.com/course/docker-and-kubernetes-the-complete-guide

## Secrets

### PGPASSWORD

For God's sake, replace xxx with your value!
`kubectl create secret generic pgpassword --from-literal PGPASSWORD=xxx`

## Install Ingress Nginx

https://kubernetes.github.io/ingress-nginx/deploy/#docker-desktop

## Kubernetes

```sh
kubectl apply -f k8s -R
kubectl delete -f k8s -R
```
