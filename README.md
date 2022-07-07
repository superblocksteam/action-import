# action-import

## About

coming soon...

## Usage

```yaml
name: superblocks
on: push
jobs:
  runs-on: ubuntu-latest
  steps:
  - uses: actions/checkout@v2
  - name: superblocks
    uses: superblocksteam/action-import@v0.1.0
    with:
      token: ${{ secrets.SUPERBLOCKS_TOKEN }}
```
