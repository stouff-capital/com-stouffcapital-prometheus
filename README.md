# prometheus monitoring

based on https://github.com/bibinwilson/kubernetes-prometheus

`kubectl create namespace monitoring`

`kubectl create -f prometheus-clusterRole.yaml`

`kubectl create -f prometheus-configMap.yaml -n monitoring`

`kubectl create -f prometheus-deployment.yaml -n monitoring`

`kubectl create -f prometheus-ingress.yaml -n monitoring`

