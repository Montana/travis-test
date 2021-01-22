[![Build Status](https://travis-ci.com/Montana/travis-test.svg?branch=master)](https://travis-ci.com/Montana/travis-test)

Messing around with `.travis.yml`. 

```yaml
language: shell

env:
  - ONE=one
  - TWO=two

jobs:
  include:
    - stage: one
      env: ONE=one
    - env: TWO=two

script: true
```
