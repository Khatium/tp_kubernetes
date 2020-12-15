# tp_kubernetes

TP Kubernetes réalisé à Ynov Bordeaux
Développé par Chambaud Mathieu et Blay Maxime

## NameSpaces

Nous avons découpé l'application en 2 namespace principaux : dev-team; prod-team;
Cela nous permet de défninir des quotas sur mesure aux namespace en fonction de leur utilité.

## Fonctionnement
1. Lancez Minikube
2. minikube service wordpress --url
3. kubectl port-forward --namespace monitoring service/grafana 3000:3000

