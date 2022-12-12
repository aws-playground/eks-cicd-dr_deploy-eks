# eks-cicd-dr_deploy-eks

## Deploy manually

* service-peccy-web

```
# Seoul
kustomize build service-peccy-web/overlays/seoul | kubectl apply -f -

# Tyoko
kustomize build service-peccy-web/overlays/tyoko | kubectl apply -f -
```

* service-peccy-app

```
# Seoul
kustomize build service-peccy-app/overlays/seoul | kubectl apply -f -

# Tyoko
kustomize build service-peccy-app/overlays/tyoko | kubectl apply -f -
```
