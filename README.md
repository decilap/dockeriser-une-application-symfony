# Un environnement de développement Symfony 5 avec Docker et Docker-compose

## Prérequis
- Docker : https://www.docker.com/get-started
- Docker-compose: https://docs.docker.com/compose/install/

## Installation

```
 docker-compose build
 docker-compose up-d
```

## Création d'un projet Symfony

```
 docker exec -it www_docker_symfony bash
 composer create-project symfony/website-skeleton project
 symfony serve -d
```