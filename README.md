#  LAMP stack built with Docker Compose
* PHP
* Apache
* MySQL
* Redis

# Docker Commands
* Stop the container(s) using the following command:
docker-compose down
* Delete all containers using the following command:
docker rm -f $(docker ps -a -q)
* Delete all volumes using the following command:
docker volume rm $(docker volume ls -q)
* Restart the containers using the following command:
docker-compose up -d