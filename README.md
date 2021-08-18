# Purpose
Gather statistics (with or without Telegraf) into influxdb and show with Grafana.

# Tools/Services
* InfluxDB - Database
* Telegraf - Server agent
* Grafana - Stats visualization
* Arris Cable Modem Stats - Gather stats from SB8200 cable modem

# Running
* Modify `docker-compose.yml` and `*.env` files
* Run `docker compose up -d`
* Use `docker compose logs -f` to follow logs
