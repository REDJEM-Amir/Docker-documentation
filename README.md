# Docker-Documentation
A GitHub project providing concise, user-friendly Docker documentation aimed at simplifying container management and deployment.

## Docker install (Ubuntu)
> https://docs.docker.com/engine/install/ubuntu/

## Basic commands

### Start docker
> sudo service docker start

### Stop docker
> sudo service docker stop

### Show active containers
> docker ps

### Show logs containers
> docker logs [idContainer]

## Cleaning the machine

### Stop all container
> docker stop $(docker ps -aq)

### Delete all container
> docker rm $(docker ps -aq)

### Delete all images
> docker rmi $(docker images -q)

### Delete all volumes
> docker volume rm $(docker volume ls -q)

### Delete all network
> docker network rm $(docker network ls -q)
