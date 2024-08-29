helm repo add schmiddim  https://schmiddim.github.io/helm-charts/
helm repo update

helm install kibana-alert-exporter kae/kibana-alert-exporter 