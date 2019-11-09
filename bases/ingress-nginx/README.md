## Updating

Copy manifests from https://github.com/kubernetes/ingress-nginx/tree/master/deploy/static.

For 0.26.1:

* configmap.yaml
* EXCLUDE: mandatory.yaml
* namespace.yaml
* rbac.yaml
* with-rbac.yaml

Also copy manifests from https://github.com/kubernetes/ingress-nginx/blob/master/deploy/static/provider.

For 0.16.1:

* cloud-generic.yaml