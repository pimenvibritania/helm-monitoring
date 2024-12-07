# Helm Monitoring

```
helm lint .
helm depedency update
helm install charts/<chart> --namespace monitoring --create-namespace -f values-<chart>.yaml
```
