# CST8915-Lab4-Docker

## Reflection Questions

### 1. What are the main differences between a Docker image and a Docker container?

A Docker image is like a template that contains everything an application needs to run. A container is what you get when you run that image. You can use the same image to run multiple containers.

### 2. How does Docker's layered architecture improve efficiency?

Docker builds images in layers, which helps save time and space. When I rebuild an image, Docker can reuse layers that haven't changed instead of rebuilding everything from scratch.

### 3. Why does each container get its own writable layer?

Each container has its own writable layer so changes made in one container don't affect the others. For example, when I changed a file in one container during the lab, the same change didn't appear in the other containers.

### 4. What are the benefits of using Docker Compose instead of running containers individually?

Docker Compose makes it easier to manage applications that use multiple containers. Instead of starting and configuring each container separately, I can define the services in one file and start them together. In this lab, it helped me run Flask and Redis as one application.

### Youtube Video
https://youtu.be/QcJ2BHArXb4
