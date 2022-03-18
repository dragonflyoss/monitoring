# Prometheus

Install prometheus and grafana based on [kube-prometheus-stack](https://artifacthub.io/packages/helm/prometheus-community/kube-prometheus-stack)

## Get Repo Info

```bash
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm repo update
```

## Install kube-prometheus-stack charts

```bash
curl -o values.yaml https://raw.githubusercontent.com/dragonflyoss/monitoring/main/prometheus/values.yaml
helm install prometheus prometheus-community/kube-prometheus-stack -f values.yaml
```
