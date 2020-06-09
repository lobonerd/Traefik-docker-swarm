# Traefik-docker-swarm
Traefik corriendo en docker-swarm para producción


![alt text](https://docs.traefik.io/assets/img/traefik-architecture.png)

##Para ejecutar el stack de Traefik
docker stack deploy -c docker-compose.yml traefik

##Para ejecutar el stack de la aplicacion
docker stack deploy -c docker-compose-app.yml app
