# CST8915-Lab4-Docker

# Lab 4 — Introduction to Docker

## Reflection Questions

### 1. What are the main differences between a Docker image and a Docker container?

A Docker image is a template containing the application and its dependencies. A container is a running instance of that image. Multiple containers can be created from the same image.

### 2. How does Docker's layered architecture improve efficiency?

Docker uses layers to store image instructions and files. When rebuilding an image, Docker can reuse unchanged layers instead of rebuilding everything, saving time and resources.

### 3. Why does each container get its own writable layer?

Each container has its own writable layer so that changes made inside one container do not automatically affect other containers using the same image. The underlying image layers can be shared.

### 4. What are the benefits of Docker Compose over running containers individually?

Docker Compose defines multiple services in one configuration file. It can build images, create networks and volumes, and start or stop connected services together. This makes multi-container applications easier to manage.
