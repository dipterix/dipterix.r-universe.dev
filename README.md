# Configuration for R-universe to Cross-Compile my Personal R packages

The goal of this repository is to compile my R packages on windows, osx, and linux. The packages in `packages.json` will be used by [r-universe](https://dipterix.r-universe.dev/ui#builds).

Some packages have already been published on CRAN. This repository provides nightly developing branches. For packages that haven't been published yet, this repository provides simple set up to install them without installing system compilers, especially for those written in *C++*.

## How to use

```
options(repos = c(
    dipterix = 'https://dipterix.r-universe.dev',
    CRAN = 'https://cloud.r-project.org'))

# Install some packages
install.packages('dipsaus')
```

Packages available are:

* https://github.com/dipterix/dipsaus - CRAN
* https://github.com/dipterix/threeBrain - CRAN
* https://github.com/dipterix/lazyarray - CRAN
* https://github.com/dipterix/spfda - CRAN
* https://github.com/dipterix/filearray - About to go CRAN
* https://github.com/dipterix/rutabaga
* https://github.com/dipterix/restbatch
