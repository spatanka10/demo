# wordpress

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] wordpress`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree wordpress`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init wordpress
kpt live apply wordpress --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
