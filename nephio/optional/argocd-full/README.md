# core-components-kustomize

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] core-components-kustomize`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree core-components-kustomize`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init core-components-kustomize
kpt live apply core-components-kustomize --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
