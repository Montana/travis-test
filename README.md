[![Build Status](https://travis-ci.com/Montana/travis-test.svg?branch=master)](https://travis-ci.com/Montana/travis-test)

Messing around with `.travis.yml`. 

```yaml
language: shell
jobs:
  include:
    - name: one
    - name: two
      if: $FOO=foo
script: true
```
