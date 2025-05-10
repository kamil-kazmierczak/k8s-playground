Minikube for local kubernetes cluster:
  - `minikube version`
  - `minikube start`
  - `minikube dashboard`

Kubectl commands:
  - `kubectl get nodes`
  - `kubectl get pods`
  - `kubectl get deployments`
  - `kubectl get services`

Get pods by label:
  - `kubectl get pods -l app=hello`

Apply config from file:
  - `kubectl apply -f pod.yaml`
  - `kubectl apply -f deployment.yaml`
  - `kubectl apply -f service.yaml`

Get into shell of running pod (interactive mode):
  - `kubectl exec -it curl-pod.yaml -- sh`

Other commands:
  - `curl hello-service`




