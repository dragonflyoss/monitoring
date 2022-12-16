# Dragonfly Monitoring

Repository contains prometheus and grafana dashboard configuration.

Deploy the prometheus and grafana using [kube-prometheus-stack](https://artifacthub.io/packages/helm/prometheus-community/kube-prometheus-stack)
charts and `prometheus/values.yaml` configuration file.

Generate grafana dashboard configuration
based on `grafana/dashboards/manager.json`, `grafana/dashboards/scheduler.json` and `grafana/dashboards/peer.json`.

## Note to developers

If developers need to publish grafana dashboard to [d7y](https://grafana.com/orgs/d7y) organization,
please contact [dragonfly maintainers](https://github.com/dragonflyoss/Dragonfly2/blob/main/MAINTAINERS.md).
