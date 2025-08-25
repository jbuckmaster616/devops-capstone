
---

### `platform/README.md`
```markdown
# Platform (Helm Charts)

This directory contains Helm charts for deploying the sample app and monitoring stack.

## Charts
- `sample-app/`: Example Flask/Node service
- `monitoring/`: Prometheus + Grafana values

## Commands
```bash
helm install sample-app ./charts/sample-app -n app
helm install monitoring prometheus-community/kube-prometheus-stack -f monitoring/prometheus-values.yaml

