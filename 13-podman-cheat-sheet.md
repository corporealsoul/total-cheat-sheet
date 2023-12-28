### Podman Basics

**podman pull [image name]:** Downloads an image from the Docker Hub or other registry.

**podman run [image name] [command]:** Runs a container from an image in the foreground.

**podman run --rm [image name] [command]:** Runs a container from an image in the background and removes it when it exits.

**podman stop [container name]:** Stops a running container.

**podman rm [container name]:** Removes a container.

**podman images:** Lists all images on the system.

**podman ps:** Lists all running containers.


### Podman Networking

**podman network create [network name]:** Creates a new network.

**podman network connect [network name] [container name]:** Connects a container to a network.

**podman network disconnect [network name] [container name]:** Disconnects a container from a network.

**podman network ls:** Lists all networks on the system.

**podman network inspect [network name]:** Inspects a network.


### Podman Volumes

**podman volume create [volume name]:** Creates a new volume.

**podman volume inspect [volume name]:** Inspects a volume.

**podman volume ls:** Lists all volumes on the system.

**podman volume rm [volume name]:** Removes a volume.


### Podman Rootless Containers

**podman run --user [username] [image name] [command]:** Runs a container as a non-root user.

**podman build --user [username] [context]:** Builds an image as a non-root user.


### Podman Security

**podman run --security-opt no-new-privileges --cap-drop=all [image name] [command]:** Runs a container with reduced privileges.

**podman run --security-opt label=unconfined [image name]:** Runs a container with the unconfined label, which allows it to access all files and devices on the system.


### Podman Advanced

**podman build [context]:** Builds an image from a Dockerfile.

**podman push [image name] [registry]:** Pushes an image to a registry.

**podman tag [image name] [new image name]:** Tags an image.

**podman import [archive] [image name]:** Imports an archive into an image.

**podman exec [container name] [command]:** Executes a command in a running container.

**podman inspect [object name]:** Inspects an object.


### Podman Troubleshooting

**podman logs [container name]:** Prints the logs for a running container.

**podman run --rm -it [image name] sh:** Creates a shell in a running container.

**podman troubleshoot:** Prints troubleshooting information.

<br>
