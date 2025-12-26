# Docker Monitoring Lab

LAB de estudos focado em boas práticas de Docker, Docker Compose e ambientes Red Hat-like.

## Estrutura
- Docker Compose versionado
- Networks dedicadas
- Volumes persistentes

## Como subir
docker compose -f compose/docker-compose.yml up -d

##Acessos
Zabbix: http://IP:8080
Grafana: http://IP:3000

## Environment variables

Copy the example file and adjust values:

```bash
cp compose/.env.example compose/.env

