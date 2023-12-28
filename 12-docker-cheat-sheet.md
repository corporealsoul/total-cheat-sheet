### Docker Images

**List Images:** `docker images`

**Pull an image from a Docker registry:** `docker pull IMAGE_NAME[:TAG]`

**Build an Image:** `docker build -t my_image .`

**Remove an Image:** `docker rmi my_image`

**Tag an image:** `docker tag IMAGE_ID NEW_IMAGE_NAME[:TAG]`


### Docker Containers

**List Running Containers:** `docker ps`

**List All Containers:** `docker ps -a`

**Start a New Container:** `docker run -d --name my_container my_image`

**Start an Existing Container:** `docker start my_container`

**Restart an Existing Container:** `docker restart my_container`

**Stop a Container:** `docker stop my_container`

**Remove a Container:** `docker rm my_container`


### Container Interaction:

**Execute a command inside a running container:** `docker exec [OPTIONS] CONTAINER COMMAND [ARG...]`

**Attach to a running container's terminal:** `docker attach CONTAINER`

**Copy files between a container and the local file system:** 
`docker cp [OPTIONS] CONTAINER:SRC_PATH DEST_PATH`
`docker cp [OPTIONS] SRC_PATH CONTAINER:DEST_PATH`


### Docker Networks

**List Networks:** `docker network ls`

**Create a Network:** `docker network create my_network`

**Connect to a Network:** `docker network connect my_network my_container`

**Disconnect from a Network:** `docker network disconnect my_network my_container`

**Remove a Network:** `docker network rm my_network`


### Docker Compose

**Start Services:** `docker-compose up -d`

**Stop Services:** `docker-compose down`

**List services in a Docker Compose project:** `docker-compose ps`


### Container Logs and Information:

**View logs of a running container:** `docker logs CONTAINER`

**Display detailed information about a container:** `docker inspect CONTAINER`


### Docker Registry:

**Push an image to a Docker registry:** `docker push IMAGE_NAME[:TAG]`

**Authenticate with a Docker registry:** `docker login REGISTRY_URL`

**Search for an image on Docker Hub:** `docker search IMAGE_NAME`


### Volume Management:

**Create a Volume:** `docker volume create my_volume`

**List Volumes:** `docker volume ls`

**Remove a Volume:** `docker volume rm my_volume`

**Create a named volume:** `docker volume create VOLUME_NAME`

**Mount a volume when running a container:** `docker run -v VOLUME_NAME:CONTAINER_PATH IMAGE_NAME`

**List all volumes:** `docker volume ls`


### Docker System:

**Show system-wide information:** `docker info`

**Clean up unused resources:** `docker system prune`

<br>
