# Configuring Azure Kubernetes Service (AKS)
This file contains text you can copy and paste for the examples in Cloud Academy's _Configuring Azure Kubernetes Service (AKS)_ course.  

### Introduction
[Azure Free Trial](https://azure.microsoft.com/free) 

### Working with a Cluster
```
az aks get-credentials --resource-group aks1 --name cluster1
kubectl get nodes
```
```
git clone https://github.com/cloudacademy/configuring-aks.git
cd configuring-aks
kubectl apply -f azure-vote.yaml
kubectl get service azure-vote-front
```

### Summary
[Azure documentation](https://docs.microsoft.com/azure/)  
support@cloudacademy.com
