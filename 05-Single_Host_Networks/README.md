# Exercise: Single Host Networks


## Commands

```
docker network create my_net
docker run --name mysql01 --network my_net -e MYSQL_ROOT_PASSWORD=dbpw -d mysql:5.7
docker run --name wordpress01 --network my_net -e WORDPRESS_DB_HOST=mysql01 -e WORDPRESS_DB_USER=root -e WORDPRESS_DB_PASSWORD=dbpw -e WORDPRESS_DB_NAME=wordpress -p 8888:80 -d wordpress
```
or
```
docker network create my_net
docker run --name mysql01 --network my_net -e MYSQL_ROOT_PASSWORD=dbpw -d mysql:5.7
docker run --name wordpress01 --network my_net -p 8888:80 -d wordpress

```
