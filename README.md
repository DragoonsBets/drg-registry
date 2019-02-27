# Hashicorp Consul

Service Mesh

## Deploy Consul in Development Namespace
kubectl apply -f ./consul-dev

## Deploy Consul in Production Namespace
kubectl apply -f ./consul-prod

## To log in to the UI you have to use port forward
kubectl port-forward <pod-name> 8500:8500

kubectl port-forward consul-0 8500:8500
kubectl port-forward consul-1 8500:8500
kubectl port-forward consul-2 8500:8500