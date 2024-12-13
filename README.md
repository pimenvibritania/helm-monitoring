# Helm Monitoring

```
helm lint .
helm depedency update
helm show values charts/<chart> > values-<chart>.yaml
helm install charts/<chart> --namespace monitoring --create-namespace -f values-<chart>.yaml
```
