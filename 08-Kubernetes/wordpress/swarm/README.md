# Exercise: Kubernetes vs Swarm: WORDPRESS


## Links

https://kubernetes.io/docs/tutorials/stateful-application/mysql-wordpress-persistent-volume/

## Steps

1. docker secret create db_root_password SecretPWR00t
2. docker secret create db_root_password SecretPWUs3r
3. docker stack deploy -f docker-compose.yml

