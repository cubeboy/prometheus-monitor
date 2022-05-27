prometheus docker image
https://hub.docker.com/r/prom/prometheus
```
docker run \
    -p 9090:9090 \
    -v /path/to/prometheus.yml:/etc/prometheus/prometheus.yml \
    prom/prometheus
```


grafana docker image
https://hub.docker.com/r/grafana/grafana
```
docker run -d --name=grafana -p 3000:3000 grafana/grafana
```