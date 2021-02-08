# monitoring-simple-example
Simple docker compose for monitoring using prometheus, grafana, alertmanager, cadvisor node-exporter and blackbox-exporter

Work in progress...

> Add to `etc/hosts` all targets you need

```
<local ip> cadvisor node prometheus 
<...> grafana
```
## Add Datasource

 * grafana:3000/datasources/new?utm_source=grafana_gettingstarted 
   
 * Select Prometheus
 
 * Add url `prometheus:9090`