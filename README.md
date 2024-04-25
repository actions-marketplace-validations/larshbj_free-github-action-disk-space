# free-github-action-disk-space
A simple workflow to free disk space on Github Action runners.

Example of how to use:
```
jobs:
  test:
    runs-on: ubuntu-22.04
    steps:
      - uses: larshbj/free-github-action-disk-space@0.0.1
        with:
          # optional and defaults to true
          print-released-space: true
```