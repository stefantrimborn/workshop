# Exercise: Kubernetes vs Swarm: WORDPRESS


## Links

https://kubernetes.io/docs/tutorials/stateful-application/mysql-wordpress-persistent-volume/

## Steps

1. Create secrets
```
kubectl create secret generic mysql-pass --from-literal=password=SuperPW
```

2. Create deployments
```
kubectl create -f mysql-deployment.yaml
kubectl create -f wordpress-deployment.yaml
```

