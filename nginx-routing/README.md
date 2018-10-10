# Web Routing example

This sample can be dployed on a single Swarm node

Pre-Req:
 - Swarm "docker swarm init" on a linux based system

### Deploy
docker stack deploy -c docker-stack-deploy-traefik.yml
docker stack deploy -c docker-stack-deploy-app.yml
