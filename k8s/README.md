




## Kubernetes Alias

Function to switch the namespace and context

Alias to switch the namespace

```
ksns() { kubectl config set-context --current --namespace="$1" }
```

Alias to switch the context 

```
ksc() { kubectl config use-context "$1" }
```

Source the RC file 
