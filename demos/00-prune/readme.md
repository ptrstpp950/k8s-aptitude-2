Create first version with:
```
k apply -f '.\step1-pod-with-service.yaml' --prune -l workshop=true
```

Then update with:
```
k apply -f '.\step2-pod-without-service.yaml' --prune -l workshop=true
```

The `svc` in created namespace `prune` will be deleted