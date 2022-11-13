# todo

```
$branch="aiw-aca4"
$instance="contosoair-$branch"

git checkout -b $branch
git push origin $branch

az account set --subscription 1234
az containerapp list --query [*].name -o tsv

az containerapp up --repo https://github.com/massimoc/ContosoAir -n $instance -g $instance -l westeurope -b $branch
az containerapp show -n $instance -g $instance

```