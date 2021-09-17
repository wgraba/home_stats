# Purpose
Gather statistics into InfluxDB and show with Grafana.

# Prereqisites
* Docker and Docker Compose
* Traefik

# Tools/Services
* InfluxDB - Database
* Grafana - Stats visualization
* Arris Cable Modem Stats - Gather stats from SB8200 cable modem

# Running
* Modify `docker-compose.yml` and `*.env` files (see `*_env_example` files)
* Run `docker compose up -d`
* Use `docker compose logs -f` to follow logs

# TODO
- [x] Recover after cable modem restart
- [ ] Send notification when cable modem restart is needed
