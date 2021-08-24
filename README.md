# Purpose
Gather statistics (with or without Telegraf) into influxdb and show with Grafana.

# Prereqisites
* Traefik

# Tools/Services
* InfluxDB - Database
* Telegraf - Metrics processor and aggregator
* Grafana - Stats visualization
* Arris Cable Modem Stats - Gather stats from SB8200 cable modem

# Running
* Modify `docker-compose.yml` and `*.env` files (see `*_env_example` files)
* Modify `telegraf/mytelegraf.conf`
* Run `docker compose up -d`
* Use `docker compose logs -f` to follow logs

# TODO
- [ ] Recover after cable modem restart
- [x] Find good Disk IO and Network stats from Telegraf
