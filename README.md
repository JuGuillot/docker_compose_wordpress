# docker_compose_wordpres

## Description
Ce projet contient une application WordPress et MySQL, orchestrée avec Docker Compose. Les mots de passe sont gérés de manière sécurisée avec **Docker Secrets**.

## Structure

- `.env` : variables non sensibles
- `secrets/` : mots de passe sensibles (non versionnés)
- `docker-compose.yml` : configuration des conteneurs

## Prérequis

- Docker
- Docker Compose

## Instructions

1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/JuGuillot/docker_compose_wordpress
   cd wordpress-docker
