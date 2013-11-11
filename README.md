Example: RODBC dependency
===========================
[![Build Status](https://travis-ci.org/csgillespie/travis-examples.png?branch=travis-RODBC2)](https://travis-ci.org/csgillespie/travis-examples)

This branch illustrates loading the `RODBC` package (used for database connections). The key line is in the `install` section:

```
    - ./travis-tool.sh aptget install r-cran-rodbc
```

This line installs the RODBC package from the ubuntu repository with all the necessary dependencies. 

Alternatively, 

```
    - ./travis-tool.sh aptget_install unixodbc-dev
```
