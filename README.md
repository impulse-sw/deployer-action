# Deployer GitHub Action

Installs [`deployer`](https://github.com/impulse-sw/deployer/) in Ubuntu to run your pipelines.

Usage example:

```yaml
jobs:
  main:
    name: main-job
    runs-on: ubuntu-latest
    steps:
      - name: Install Deployer
        uses: impulse-sw/deployer-action@0.2
      - name: Run pipeline
        run: |
          depl run pipeline-name
```
