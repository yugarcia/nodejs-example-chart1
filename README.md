# nodejs-example-chart

### Paso pre-instalacion
```Bash
kubectl apply -f ./template/secret.yaml -n helm-chart
```
### instalar una aplicacion

```bash
helm install nodejs-example-chart . -f values.yaml  --debug -n helm-chart
```

### para hacer debug

```Bash
helm install nodejs-example-chart . -f values.yaml  --debug -n helm-chart
```
```Bash
helm install nodejs-example-chart . -f values.yaml  --debug -n helm-chart --dry-run
```
### desinstalar una aplicacion
```Bash
helm uninstall nodejs-example-chart -n helm-chart
```