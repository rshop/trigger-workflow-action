# Trigger workflow action

This action triggers workflow on another repository.

## Inputs

### `repository`

**Required** Repository to trigger workflow on.

### `branch`

**Required** Branch to use workflow from. Default `'main'`.

## Example usage

```
uses: rshop/trigger-workflow-action@v1
with:
  repository: 'rshop/pipeline'
```