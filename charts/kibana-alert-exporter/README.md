# Kibana Alert Exporter Helm Chart

# Installation + Configuration
## Installation
```bash 
helm repo add schmiddim  https://schmiddim.github.io/helm-charts/
helm repo update

helm upgrade kibana-alert-exporter schmiddim/kibana-alert-exporter --install  
```
## Configuration
Create a [Kibana Auth Token](https://www.elastic.co/guide/en/kibana/current/kibana-authentication.html#token-authentication) and store it in a Secret
```bash
kubectl create secret generic kibana-api-token --from-literal=KIBANA_AUTH_TOKEN=SuPeRS3cretToken
```

# Uninstall 
```bash
helm uninstall kibana-alert-exporter
```
