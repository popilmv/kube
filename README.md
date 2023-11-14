# kube
We have docker image in Docker hub with go app
Now we apply this in google cloud
In Deploymant we describe numbers oа replica, name and define docker image 
In Service we point our type and ports than we need

To apply this i use command
```
kubectl apply -f my-deployment.yaml && kubectl apply -f my-service.yaml
```
And check information on my cluster IP
```
kubectl get services
```
