# Teloggy.Charts
Public Charts


# ¿Do you want to use?


## Install with helm
```bash
helm repo add teloggy https://teloggy-opencommunity.github.io/Teloggy.Charts
```

## Deploy Solution default
```bash
helm install example teloggy -n default
```


## Deploy Solution override values
```bash
helm install example teloggy/chart-microservices -f /path/values.yaml -n default
```
