# Docker Swarm Monitoring

Docker Swarm Monitoring it is a simple and fast way to monitoring your cluster, using Telegraf, InfluxDB e Grafana.

## Deploy

```bash
$ git clone https://github.com/alexgracianoarj/docker-swarm-monitoring.git
$ cd docker-swarm-monitoring
$ docker build -t grafana/grafana:monitoring ./grafana
$ docker stack deploy -c docker-compose.yml monitoring
```