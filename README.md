# envoy-rate-limit

## Steps to apply 

1. kubectl apply -f 1.namespace.yaml
2. kubectl apply -f 2.app-dep.yaml
3. kubectl apply -f 3.app-svc.yaml
4. kubectl apply -f 4.gateway.yaml
5. kubectl apply -f 5.virtual-service.yaml
6. kubectl apply -f 6.rate-limit-service.yaml
7. kubectl apply -f 7.rate-limit-envoy-filter.yaml
8. kubectl apply -f 8.deny
