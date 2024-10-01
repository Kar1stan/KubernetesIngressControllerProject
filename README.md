# KubernetesIngressControllerProject
***
Simple kubernetes deployment manifect creating LoadBalancer service with 2 containers.

## 💻 Pre-requisites

Before you use this project you need to have Docker installed in your computer,and also Minikube.

https://www.docker.com/products/docker-desktop/
https://minikube.sigs.k8s.io/docs/start/?arch=%2Fwindows%2Fx86-64%2Fstable%2F.exe+download

### Git clone
This will clone the project:
```
$ git clone https://github.com/Kar1stan/KubernetesIngressControllerProject.git
$ cd KubernetesIngressControllerProject
```

## 🚀 Run the manifest: 
To run the ingress controller,open the terminal and run:
```
$ kubectl apply -f ingress-myweb-v1.yaml
```
To delete ingress controller,open the terminal and run:
```
$ kubectl delete ingress ingress-myweb-v1
```
To show details of the ingress,open the terminal and run:
```
$ kubectl describe ingress ingress-hosts
```
