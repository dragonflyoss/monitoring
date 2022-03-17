# Dragonfly Monitoring

Repository contains prometheus and grafana dashboard configuration.

Deploy the prometheus and grafana using [kube-prometheus-stack](https://artifacthub.io/packages/helm/prometheus-community/kube-prometheus-stack)
charts and `prometheus/values.yaml` configuration file.

Generate grafana dashboard based on `grafana/dashboards/manager.json`, `grafana/dashboards/scheduler.json` and `grafana/dashboards/cdn.json`.
