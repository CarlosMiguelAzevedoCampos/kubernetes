# 1. Install kubernetes

https://kubernetes.io/docs/tasks/tools/install-kubectl-windows/

# 2. Install Minikube

https://minikube.sigs.k8s.io/docs/start/?arch=%2Fwindows%2Fx86-64%2Fstable%2F.exe+download

# 3. Important commands

kubectl get/delete/edit pods - returns the pods

kubectl get/delete/edit rs - returns ReplicaSet

kubectl get/delete/edit deployment - returns the deployment

kubectl get/delete/edit services - returns the services

kubectl get nodes - returns the nodes

kubectl scale deployment [deploy-name] --replicas=5 - changes the number of replicas

minikube service voting-service --url - returns the URL of the service

kubectl logs [pod-name]