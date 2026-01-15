# ocp-configs
### Install argocd operator + instance
```bash
oc apply -f argocd-operator/ns.yaml
oc apply -f argocd-operator/
oc apply -f argocd/apps-in-apps/
```


### Install app-in-app Application
```bash
oc apply -f openshift-cluster/cluster-sec/argocd/apps-in-apps/
```
