# Minikube-Pods-Deployments-and-Services

![image](https://github.com/biplobpustcse/Minikube-Pods-Deployments-and-Services/assets/59637279/4856e65b-6416-47e2-b596-c1759dffa132)

![image](https://github.com/biplobpustcse/Minikube-Pods-Deployments-and-Services/assets/59637279/e0265d0b-e868-40ad-99e0-d122000c5ee9)

![image](https://github.com/biplobpustcse/Minikube-Pods-Deployments-and-Services/assets/59637279/3e45640a-bc19-4f45-8d62-96a11233cac4)

![image](https://github.com/biplobpustcse/Minikube-Pods-Deployments-and-Services/assets/59637279/4ee95a04-9c68-4241-815b-302bc88e8720)


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
