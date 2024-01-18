# argocd-private-deployment 

use this command for giving permission to minikube for pulling private docker image on dev namespace 
```bash
kubectl create secret docker-registry docker-registry-dev \
  --namespace=dev \
  --docker-username=panchanandevops \
  --docker-email=panchanandevops@gmail.com \
  --docker-password=dckr_pat_CcCX8sJJY_MOQ-S64QePViXmhAk

```
use this command for giving permission to minikube for pulling private docker image on staging namespace

```bash
kubectl create secret docker-registry docker-registry-staging \
  --namespace=staging \
  --docker-username=panchanandevops \
  --docker-password=dckr_pat_CcCX8sJJY_MOQ-S64QePViXmhAk \
  --docker-email=panchanandevops@gmail.com

```
