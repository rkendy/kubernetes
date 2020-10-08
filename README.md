# kubernetes

## Local machine (Windows 10)
* Install docker
* Install Kind (https://kind.sigs.k8s.io/docs/user/quick-start)
* Manage cluster:



```
# Create cluster using yaml file:
$ kind create cluster --name mycluster --config ./kind/config.yaml

# Get clusters:
$ kind get clusters

# Delete cluster:
$ kind delete cluster --name mycluster

# Get nodes:
$ kubectl get nodes

# List containers:
$ docker ps
```
