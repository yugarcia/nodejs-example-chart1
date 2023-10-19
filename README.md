# nodejs-example-chart

### Clonar el repo y posicionarse en la carpeta del cahrt.
```bash
git clone https://https://github.com/edgaregonzalez/nodejs-example-chart.git
cd nodejs-example-chart/helm-chart
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