# @brightspace-ui/browserslist-config

Shareable [browserslist](https://github.com/browserslist/browserslist) configuration for D2L applications.

Use from `package.json`:

```json
"browserslist": [
  "extends @brightspace-ui/browserslist-config"
]
```

Or `.browserslistrc`:

```
extends @brightspace-ui/browserslist-config
```

## Versioning and Releasing

This repo is configured to use `semantic-release`. Commits prefixed with `fix:` and `feat:` will trigger patch and minor releases when merged to `main`.

To learn how to create major releases and release from maintenance branches, refer to the [semantic-release GitHub Action](https://github.com/BrightspaceUI/actions/tree/main/semantic-release) documentation.
