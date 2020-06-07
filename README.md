# github-actions 

actions for github workflows

## Example of usage

```
jobs:
  build:
    runs-on: ubuntu-latest
      name: Build image job
        steps:
          - name: Checkout master
            uses: actions/checkout@master
          - name: ...
            uses: xoroxwb/github-actions/<action>@master
            with:
              ...
```
# available actions:

- docker-buildx