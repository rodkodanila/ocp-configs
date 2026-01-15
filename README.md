# Install GITOPS AND VAULT
```bash
kubectl apply -k bootstrap/openshift-gitops
kubectl apply -k bootstrap/vault-secret-operator
```


### Install app-in-app Application
```bash
oc apply -f openshift-cluster/cluster-sec/argocd/apps-in-apps/
```
