
<!-- README.md is generated from README.Rmd. Please edit that file -->

[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![Travis Build
Status](https://travis-ci.org/IndrajeetPatil/devtoolverse.svg?branch=master)](https://travis-ci.org/IndrajeetPatil/devtoolverse)
[![AppVeyor Build
Status](https://ci.appveyor.com/api/projects/status/github/IndrajeetPatil/devtoolverse?branch=master&svg=true)](https://ci.appveyor.com/project/IndrajeetPatil/devtoolverse)

# devtoolverse

The goal of `devtoolverse` is to make it easy to install and
subsequently load packages needed for development of R packages.

## Installation

You can install the `devtoolverse` from `GitHub`:

``` r
devtools::install_github("IndrajeetPatil/devtoolverse")
```

Loading the package-

``` r
## load devtoolverse
library(devtoolverse)
#> -- Attaching packages ------------------------------------------------------------------------------ devtoolverse 0.0.0.9000 --
#> v available    1.0.2          v lintr        1.0.3     
#> v bench        1.0.1          v goodpractice 1.0.2     
#> v desc         1.2.0          v pkgdown      1.2.0.9000
#> v pkgverse     0.0.1          v usethis      1.4.0.9000
#> v pkgbuild     1.0.2          v testthat     2.0.1     
#> v pkgload      1.0.2          v spelling     1.2       
#> v rcmdcheck    1.3.2          v rhub         1.0.2     
#> v remotes      2.0.2          v roxygen2     6.1.1     
#> v sessioninfo  1.1.1          v sinew        0.3.8     
#> v covr         3.2.1          v styler       1.1.0     
#> v exampletestr 1.4.1
#> 
```

If and when they are released on `CRAN`, the following pacakges will
also be included-

  - covrpage (<https://github.com/yonicd/covrpage>)
  - defender (<https://github.com/ropenscilabs/defender>)
  - gramr (<https://github.com/ropenscilabs/gramr>)
  - packagemetrics (<https://github.com/ropenscilabs/packagemetrics>)
  - revdepcheck (<https://github.com/r-lib/revdepcheck>)
  - tic (<https://github.com/ropenscilabs/tic>)

If there are other R packages that you think are important for package
development, please raise an issue or make a PR.

For a more detailed account about how to develop R packages, see the
following textbook by Hadley Wickham- <http://r-pkgs.had.co.nz/>

## Code of Conduct

Please note that the `devtoolverse` project is released with a
[Contributor Code of Conduct](CODE_OF_CONDUCT.md). By contributing to
this project, you agree to abide by its terms.
