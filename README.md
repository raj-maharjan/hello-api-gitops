# hello-api-gitops

GitOps desired state for the `hello-api` Kubernetes app.

Argo CD should watch:

```text
path: apps/hello-api
namespace: default
```

The image path is configured in:

```text
apps/hello-api/kustomization.yaml
```
