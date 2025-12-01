# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/brettmbates/argocd-example-apps
# cd into the cloned directory
git checkout ffc866600c08a644126df76ae5d3dae8c17beade
helm template . --name-template prod-helm-guestbook --include-crds
```
