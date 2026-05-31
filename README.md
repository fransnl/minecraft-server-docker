# minecraft-server-docker
A quickstart for a minecraft server using docker, itzg/minecraft-server and traefik as a reverse proxy. Ready to start but recommended to edit docker-compose file in server for desired version and ram.

## Steps to start
* Create docker network named "proxy"
* Run **docker compose up** in proxy folder
* Add desired mods in /server/mods folder
* Change docker compose file to desired minecraft version, modloader etc
* Run **docker compose up** in server folder


