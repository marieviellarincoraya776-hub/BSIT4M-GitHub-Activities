# Docker Deployment & Lifecycle Management

## Lifecycle Commands Executed
1. `docker ps` - Lists all currently running containers in the Docker environment.
2. `docker stop web-server` - Gracefully halts the execution of the active Nginx web server container.
3. `docker ps` (Verification) - Confirms that the container has successfully stopped.
4. `docker rm web-server` - Permanently deletes the stopped container instance to free up resources.
