## Create kubernetes cluster
```bash
    kind create cluster --config=k8s/kind.yaml --name=k8s-app
```


## Create Pod
```bash
    kubectl apply -f k8s/pod.yaml
```

## Create Replicaset
```bash
    kubectl apply -f k8s/replicaset.yaml
```

## Create Deployment
```bash
    kubectl apply -f k8s/deployment.yaml
```