


docker logs [id container o nombre del container]

docker exec -it 77999a4f6e9f bash


Docker RUN

 
 docker run --name mysql -p 3307:3306 -e MYSQL_ROOT_PASSWORD=123456789 -d  mysql:lts

 docker volume
 docker volume ls
 dcoker volume prune <codigo del volumen>
 docker volume inspect <codigo del volumen>

 docker network
 docker network ls
 docker network prune
 docker network inspect <codigo de la red>
 docker network rm <codigo de la red>


 docker inspect <codigo del contenedot>


# Docker Compose 


 docker compose -f 'dockercompose\database\mysql-phpmyadmin\docker-compose.yml' up -d --build

 docker compose -f 'docker/docker-compose/mysql-phpmyadmin/docker-compose.yml' down