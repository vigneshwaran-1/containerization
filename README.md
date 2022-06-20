# Containerize Application Stack
Spell Check - 
[![CI - Spell Check](https://github.com/vigneshwaran-1/containerization/actions/workflows/spellcheck.yaml/badge.svg)](https://github.com/vigneshwaran-1/containerization/actions/workflows/spellcheck.yaml)


Docker setup for running mysql server and client in two different containers and connecting them via bridge. This gives a basic knowledge about basic docker commands , docker services , docker-compose , docker conatiners and docker networks and then to spin up the requirments quickly using docker 

The Docker-compose file comprises of the following
- Docker Network with bridge driver type  
- MySQL Server 5.X
- Alpine Linux Server with MySQL Client Installed



## CI Pipeline

- Spell Check Against the soruce files
- Validate Docker Compose

### Execution

- Install Docker Desktop , WSL2 Linux Sub-system
- Checkout repository
- Navigate in to infrastructure directory
- Execute the below command in terminal

```sh
cd infrastructure
docker compose -f docker-compose.yaml up
```