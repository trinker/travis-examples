Example: XML dependencies
==========================
[![Build Status](https://travis-ci.org/csgillespie/travis-examples.png?branch=travis-xml)](https://travis-ci.org/csgillespie/travis-examples)

This branch illustrates having multiple packages in a single repository. The key line is in the `install` section:

```
    - ./travis-tool.sh aptget install r-cran-xml 
```

This lines installs the XML package from the ubuntu repository with all the necessary dependencies.
