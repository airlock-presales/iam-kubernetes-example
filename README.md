# iam-kubernetes-example
This example should help to get the IAM running in Kubernetes

```bash
kubectl kustomize --enable-helm manifests/iam | kubectl apply --server-side -f -
```
# Now you can access the IAM:

https://iam-127-0-0-1.nip.io/auth-admin