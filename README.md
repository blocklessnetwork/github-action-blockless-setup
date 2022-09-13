# Blockless Action Setup

Sets up the Github Runner environment to operate within the Blockless network.

## Example usage

Simply add this action to your runner steps.

```yaml
jobs:
  publish-on-blockless:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: Blockless Action Setup
        uses: txlabs/github-action-blockless-setup@v0.0.1
```
