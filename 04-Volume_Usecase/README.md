# Exercise: Container Basics


## Commands

```
NAMED VOLUMES: 
docker container run -d --name httpd -v httpd:/usr/local/apache2/htdocs httpd

Bind Mounts: 
docker container run -d --name httpd -p 80:80 -v $(pwd):/usr/local/apache2/htdocs httpd

```
