




##Kubernetes Alias


Alias to switch the namespace

```
ksns() { kubectl config set-context --current --namespace="$1" }
```

Alias to switch the context 

```
ksc() { kubectl config use-context "$1" }
```

Sournce the RC file 
