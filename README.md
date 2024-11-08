# devops4cloudk8s
Ferramentas:
- docker
- kubectl
- kd3 ou minikube
```
k3d cluster create
```
```
kubectl get nodes
```
```
k3d cluster list
```
```
k3d cluster delete
```
```
k3d cluster create nxt-cluster --servers 3 --agents 3
k3d cluster create nxt-cluster --servers 3 --agents 3 -p "30000:30000@loadbalancer"
```
```
kubectl api-resources
```
```
kubectl create -f deployment.yaml
kubectl apply -f deployment.yaml
```
```
kubectl get pods
```
```
kubectl get deployments
```
```
kubectl describe pod conversao-distancia-c9469db5f-v5m92
```
```
kubectl get replicasets
```
```
kubectl get replicaset,pods
```
```
kubectl apply -f deployment.yaml && watch 'kubectl get pods'
```
```
kubectl get pod -o wide
```
```
kubectl port-forward pod/conversao-distancia-c9469db5f-z78hr 8080:5000
```
```
kubectl get all
```
```
kubectl port-forward service/conversao-distancia 8686:80
```
```