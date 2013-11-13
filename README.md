Example: XML dependencies
==========================
[![Build Status](https://travis-ci.org/csgillespie/travis-examples.png?branch=travis-vignette)](https://travis-ci.org/csgillespie/travis-examples)

This branch illustrates having an `XML` dependency. The key line is in the `install` section:

```
    - ./travis-tool.sh aptget install r-cran-xml 
```

This line installs the `XML` package from the ubuntu repository with all the necessary dependencies.
