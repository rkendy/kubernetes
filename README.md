# kubernetes

## Local machine (Windows 10)
* Install docker
* Install Kind (https://kind.sigs.k8s.io/docs/user/quick-start)
* Manage cluster:
```
$ kind create cluster --name mycluster
$ kind get clusters
$ kind delete cluster --name mycluster
$ kind create cluster --name mycluster --config ./kind/config.yaml
```
