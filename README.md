# Demo of setting up helm chart and kustomize

## Install helm chart

From within exochart dir, execute below command

`
helm install exoplanets .
`

## Upgrade helm chart, usually after code changes

From whithin exochart dir, execute below command

`
helm upgrade exoplanets .
`

## Apply kustomize test profile

From within exokustom dir, execute below command

`
kubectl apply -k base

kubectl apply -k overlays/test
`
