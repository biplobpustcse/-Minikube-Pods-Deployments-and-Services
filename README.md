# Minikube-Pods-Deployments-and-Services

#### get deployments (cmd)
```
kubectl get deployments
```
#### deployments (cmd)
```
kubectl create deployment <deployment name> --image=<image name>
```
```
kubectl create deployment nginx-depl --image=nginx
```
#### get deployment list
```
kubectl get deployment
```
#### get pods list
```
kubectl get pods
```
#### expose deployment by creating a service
```
kubectl expose deployment <deployment name> --type=NodePort --name=<service name> --port=<port no>
```
```
kubectl expose deployment nginx-depl --type=NodePort --name=ex-nginx-service --port=80
```
```
kubectl get services
```
#### url of a service
```
minikube service --url <service name>
```
```
minikube service --url ex-nginx-service
```
