# Exercise: Container Basics


## Commands

```
docker container run --publish 80:80 nginx
docker container run --publish 80:80 --detach --name webhost nginx
docker container ls
docker container stop

docker container exec -it webhost sh

docker container run -it alpine sh
```
