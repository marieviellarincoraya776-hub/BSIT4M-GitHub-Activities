# Laboratory 4: The Cloud-Native Engineer

## Mission Overview
Successfully transitioned from traditional virtual machines to containerized cloud architectures by evaluating virtual machines versus containers, launching a Docker playground environment, deploying an Nginx web server, and managing container lifecycles using the Docker CLI.

## Objectives
* Differentiate between traditional Virtual Machines (VMs) and Containers.
* Access a Docker-enabled cloud environment using KillerCoda.
* Execute fundamental Docker CLI commands.
* Pull, run, manage, and terminate a containerized application (Nginx).
* Create professional technical documentation using Markdown.

## Docker Commands Executed
* `docker --version` & `docker info` - Verified the Docker installation and environment status.
* `docker pull nginx` - Downloaded the official Nginx image from Docker Hub.
* `docker run -d -p 8080:80 --name web-server nginx` - Ran the Nginx container in detached mode with port mapping.
* `curl http://localhost:8080` - Verified local HTTP response from the running web server.
* `docker ps` - Listed active containers.
* `docker stop web-server` - Halted the running Nginx container.
* `docker rm web-server` - Permanently removed the stopped container instance.

## Skills Learned
* Understanding architectural differences between VMs and containers.
* Executing core container management and lifecycle commands via the CLI.
* Configuring port mappings for containerized web applications.
* Maintaining technical documentation using Markdown and GitHub repositories.

## Challenges Encountered
Ensured proper syntax alignment when executing Docker commands and correctly mapping host-to-container ports during deployment.
