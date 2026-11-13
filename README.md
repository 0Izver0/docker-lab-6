# Kubernetes: Deployment з YAML (Minikube)

Практична робота №6, варіант 3: Deployment з 2 репліками образу nginx.
    minikube start
    kubectl get nodes
    kubectl apply -f deployment.yaml
    kubectl get deployments
    kubectl get pods

Очищення:
    kubectl delete -f deployment.yaml
    minikube stop
