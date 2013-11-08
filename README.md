Example: Multiple packages
==========================
[![Build Status](https://travis-ci.org/csgillespie/travis-examples.png?branch=multiple-packages)](https://travis-ci.org/csgillespie/travis-examples)

This branch illustrates having multiple packages in a single repository. The key lines are:

```
before_install:
    - cd $REPO_TO_TEST
```

and 
```
env:
  matrix:
        - REPO_TO_TEST=badpackage
        - REPO_TO_TEST=goodpackage
```



Example of using r-travis on a repo with multiple packages.
