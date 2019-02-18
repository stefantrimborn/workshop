# Exercise: Kubernetes vs Swarm: WORDPRESS


## Links

https://docs.docker.com/compose/wordpress/

## Steps


1. Create secrets
```
echo SecretPWR00t | docker secret create db_root_password -
echo SecretPWUs3r | docker secret create db_dba_password -
```

2. Deploy COMPOSE File
```
docker stack deploy -f docker-compose.yml WORDPRESS
```


