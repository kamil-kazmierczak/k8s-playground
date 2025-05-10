minikube version
minikube start

kubectl get nodes
kubectl get pods
kubectl get deployments
kubectl get services

kubectl get pods -l app=hello

kubectl apply -f pod.yaml
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

kubectl exec -it curl-pod.yaml
curl hello-service



