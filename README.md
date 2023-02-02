# Learning-Kubernetes

- minikube start
- kubectl create namespace argoctl
- kubectl apply -n argocd -f deployment.yaml 
- kubectl get deployments
- kubectl port-forward gotest-deployment-b7c99b56-5g76p 8090:8090  (curl localhost:8090 in different terminal)
- kubectl apply -n argoctl -f service.yaml
- minikube start service learnkubernetes-service -n argocd
