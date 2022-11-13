# Draft

https://learn.microsoft.com/en-us/cli/azure/aks/draft?view=azure-cli-latest

```
# pre-requisite
az aks draft setup-gh --app=contosoair-aksap --provider=azure --subscription-id=533f6b10-3a70-4c5d-8962-8b51e839a13c --resource-group=fabmedical-aiw --gh-repo=MassimoC/ContosoAir

# create docker file + manifest/helm/kustomize
az aks draft create 

# create gh action
az aks draft generate-workflow

az aks draft generate-workflow --branch=main-aks --resource-group=fabmedical-aiw --cluster-name=fabmedicalaiw --registry-name=fabmedicalaiw --container-name=contosoair 

```