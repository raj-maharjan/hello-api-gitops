# hello-api-gitops

GitOps desired state for the `hello-api` Kubernetes app.

Argo CD should watch:

```text
path: apps/hello-api
namespace: default
```

Before using this repo, replace `YOUR_GITHUB_USERNAME` in:

```text
apps/hello-api/kustomization.yaml
```
