# Traditional Chinese Lint

Traditional Chinese Lint for check words

## Use Actions

Workflow YAML example:

```yaml
jobs:
  lint:
    runs-on: ubuntu-latest
    name: Lint

    steps:
      - name: Checkout code
        uses: actions/checkout@v4

      - name: Lint
        uses: MilesChou/traditional-chinese-lint@master
        with:
          paths: .
```