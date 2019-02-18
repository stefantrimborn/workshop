# Exercise: Kubernetes vs Swarm: WORDPRESS


## Links

https://kubernetes.io/docs/tutorials/stateful-application/mysql-wordpress-persistent-volume/

## Steps

1. echo SecretPWR00t | docker secret create db_root_password -
2. echo SecretPWUs3r | docker secret create db_dba_password -
3. docker stack deploy -f docker-compose.yml WORDPRESS

