# Deploy docker container with zero downtime using blue/green deployment

<br>

Make sure you edit the service_name same as with service name in docker_compose_name

<br>

Example in production.sh :
```
service_name=app-production
docker_compose_name=docker-compose.production.yml
```

Example in docker-compose.production.yml :
```
services:
  app-production:
    image: app/production
```
