# Docker

## What is Docker?
Docker is a platform for developing, shipping, and running applications in containers.

## Architecture
- Docker Engine: Core component to build and run containers.
- Images: Read-only templates for containers.
- Containers: Running instances of images.
- Docker Hub: Registry for sharing images.

## Example Dockerfile
```dockerfile
FROM nginx:latest
COPY index.html /usr/share/nginx/html/index.html
```
