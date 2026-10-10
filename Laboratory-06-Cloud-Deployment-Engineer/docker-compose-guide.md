# Docker Compose Technical Guide

## Understanding the Configuration

* **What does the `services:` block do?**
  The `services:` block defines the individual containers that make up your multi-container application stack. Each service specifies its own container image, environment variables, port mappings, and networking parameters, allowing Docker Compose to manage them as a unified application.

* **How did the Nextcloud app container know how to find the database container?**
  Through the `MYSQL_HOST=database` environment variable coupled with Docker Compose's built-in automatic DNS resolution. Docker Compose automatically creates a default bridge network where each service name resolves directly to its respective container's IP address on that network.

* **What is the difference between `docker run` and `docker-compose up -d`?**
  `docker run` requires manual execution of lengthy command-line flags for networking, volumes, environment variables, and ports one container at a time. In contrast, `docker-compose up -d` is a declarative Infrastructure as Code (IaC) approach that provisions and runs an entire multi-container stack in the background using a single configuration file.
