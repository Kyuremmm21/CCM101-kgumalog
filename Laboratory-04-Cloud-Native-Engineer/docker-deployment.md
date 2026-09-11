# Docker Deployment – Container Lifecycle

1. `docker ps`  
   Lists all currently running containers.

2. `docker stop my-nginx`  
   Gracefully stops the running Nginx container.

3. `docker ps -a`  
   Shows all containers (including stopped ones) so we can confirm the container is no longer running.

4. `docker rm my-nginx`  
   Permanently deletes the stopped container from the system.
