# todo

```
az containerapp list

$instance="contosoair-aca2"

az containerapp up --repo https://github.com/massimoc/ContosoAir -n $instance -g $instance -l westeurope -b main-aca-aiw

az containerapp show -n $instance -g $instance
```