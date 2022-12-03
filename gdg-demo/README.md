# gdg-demo

## Description


## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] gdg-demo`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree gdg-demo`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init gdg-demo
kpt live apply gdg-demo --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
