Example: XML dependencies
==========================
[![Build Status](https://travis-ci.org/csgillespie/travis-test.png?branch=travis-xml)](https://travis-ci.org/csgillespie/travis-test)

This branch illustrates having multiple packages in a single repository. The key line is in the `before_install` section:

```
    - ./travis-tool.sh aptget install r-cran-xml 
```

This lines installs the XML package from the ubuntu repository with all the necessary dependencies.