# ocp-configs
### Install argocd operator + instance
```bash
oc apply -f argocd-operator/ns.yaml
oc apply -f argocd-operator/
oc apply -f argocd/apps-in-apps/
```