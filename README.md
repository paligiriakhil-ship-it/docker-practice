# Docker Practice

## Overview

This repository contains Docker concepts, labs, commands, Dockerfiles and containerization projects.

---

## Concepts Covered

- Docker Installation
- Images
- Containers
- Dockerfile
- Volumes
- Networks
- Docker Compose
- Registries
- Port Mapping

---

## Useful Commands

```bash
docker images

docker ps

docker ps -a

docker run nginx

docker stop container_id

docker rm container_id

docker build -t myapp .

docker logs container_id

docker exec -it container_id bash
```

---

## Sample Dockerfile

```dockerfile
FROM nginx

COPY . /usr/share/nginx/html

EXPOSE 80
```

---

## Projects

Food Ordering Application

Ticket Management Application

3 Tier Application Deployment

---

## Future Enhancements

Docker Compose

Private Registry

CI/CD Integration

Kubernetes Deployment
