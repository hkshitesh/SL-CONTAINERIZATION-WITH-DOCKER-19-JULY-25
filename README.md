## Docker Commands

# Image Command

docker images   -> list all docker images in your local system

docker image ls

docker pull <image name> 

docker rmi <image-name>

docker build


# Conatiners Commands
docker run

	docker run -it <img-name> /bin/bash   (cli based container)
	docker run -p 8004:80 nginx	
 	docker exec -it <cont-id> /bin/bash

docker ps     ->list all running containers

docker ps -a     ->list all running/not running containers

docker start <cont-id>

docker stop <cont-id>

docker rm <cont-id>
