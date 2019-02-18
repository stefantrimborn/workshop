# Exercise: Kubernetes vs Swarm: WORDPRESS


## Links

https://kubernetes.io/docs/tutorials/stateful-application/mysql-wordpress-persistent-volume/

## Steps

1. kubectl create secret generic mysql-pass --from-literal=password=SuperPW
2. kubectl create -f mysql-deployment.yaml
3. kubectl create -f wordpress-deployment.yaml

