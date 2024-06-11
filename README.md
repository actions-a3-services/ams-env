# Get Git describe

This action fetches and describes the latest Git tag.

## Usage

```yaml
uses: your-username/your-repo@v1
```

## Example Workflow
```yaml
name: Example workflow
on: [push]
jobs:
  example:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: your-username/your-repo@v1
```

## Inputs
```
None
```

## Outputs
```
AMS_REVISION: The latest Git tag description.
``