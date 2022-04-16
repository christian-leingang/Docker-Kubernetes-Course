# Code-Ablage zum Docker-Kubernetes-Kurs
Dieses Repository dient als Ablage der Übungsaufgaben aus dem Onlinekurs auf [Udemy](https://www.udemy.com/course/docker-kubernetes-the-practical-guide/)


Notizen zum Starten des Kubernetes-Clusters:

- minikube start
- kubectl apply -f deployment.yaml und service.yaml
- minikube service backend
- kubectl port-forward service/story-service 32420:80 --address='0.0.0.0' (localhost-Port:Service-Port neues Terminal)
- Verfügbar auf localhost:7080

Get Pods: kubectl get pods
