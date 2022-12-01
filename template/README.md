# template

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] template`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree template`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init template
kpt live apply template --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
