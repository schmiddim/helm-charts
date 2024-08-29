## Install
```bash 
helm repo add schmiddim  https://schmiddim.github.io/helm-charts/
helm repo update

helm upgrade kibana-alert-exporter schmiddim/kibana-alert-exporter --install  
```

## Local setup
```bash 
helm upgrade   local-setup .  --install
```



## Action Documentations
https://github.com/helm/chart-releaser-action?tab=readme-ov-file#example-workflow
