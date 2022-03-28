Start kubernetes:

- minikube start
- kubectl apply -f deployment.yaml und service.yaml
- minikube service backend
- kubectl port-forward service/backend 7080:8080 (neues Terminal)
- Verfügbar auf localhost: 7080

Get Pods: kubectl get pods
