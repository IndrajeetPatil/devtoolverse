
<!-- README.md is generated from README.Rmd. Please edit that file -->

[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![Travis Build
Status](https://travis-ci.org/IndrajeetPatil/rpkgtools.svg?branch=master)](https://travis-ci.org/IndrajeetPatil/rpkgtools)
[![AppVeyor Build
Status](https://ci.appveyor.com/api/projects/status/github/IndrajeetPatil/rpkgtools?branch=master&svg=true)](https://ci.appveyor.com/project/IndrajeetPatil/rpkgtools)
[![CircleCI](https://circleci.com/gh/IndrajeetPatil/rpkgtools.svg?style=svg)](https://circleci.com/gh/IndrajeetPatil/rpkgtools)

# rpkgtools

The goal of `rpkgtools` is to make it easy to install and subsequently
load packages needed for development of R packages.

## Installation

You can install the `rpkgtools` from `GitHub`:

``` r
devtools::install_github("IndrajeetPatil/rpkgtools")
```

Loading the package-

``` r
## load rpkgtools
library(rpkgtools)
#> -- Attaching packages --------------------------------------------------------------------------------- rpkgtools 0.0.0.9000 --
#> v available    1.0.2          v goodpractice 1.0.2     
#> v bench        1.0.1          v pkgdown      1.3.0     
#> v desc         1.2.0          v usethis      1.4.0.9000
#> v pkgverse     0.0.1          v testthat     2.0.1     
#> v pkgbuild     1.0.2          v spelling     1.2       
#> v pkgload      1.0.2          v RTest        1.2.1     
#> v rcmdcheck    1.3.2          v rhub         1.0.2     
#> v remotes      2.0.2          v roxygen2     6.1.1     
#> v sessioninfo  1.1.1          v sinew        0.3.8     
#> v covr         3.2.1          v styler       1.1.0     
#> v exampletestr 1.4.1          v vdiffr       0.2.3     
#> v lintr        1.0.3
#> -- Conflicts ----------------------------------------------------------------------------------------- rpkgtools_conflicts() --
#> x RTest::summary() masks base::summary()
```

If and when they are released on `CRAN`, the following pacakges will
also be included-

  - attachment (<https://github.com/ThinkR-open/attachment>)
  - covrpage (<https://github.com/yonicd/covrpage>)
  - defender (<https://github.com/ropenscilabs/defender>)
  - gramr (<https://github.com/ropenscilabs/gramr>)
  - packagemetrics (<https://github.com/ropenscilabs/packagemetrics>)
  - pRojects (<https://github.com/lockedata/pRojects>)
  - revdepcheck (<https://github.com/r-lib/revdepcheck>)
  - roxygen2Comment (<https://github.com/csgillespie/roxygen2Comment>)
  - roxygen2md (<https://github.com/r-lib/roxygen2md>)
  - testdown (<https://github.com/ThinkR-open/testdown>)
  - tic (<https://github.com/ropenscilabs/tic>)

If there are other R packages that you think are important for package
development, please raise an issue or make a PR.

For a more detailed account about how to develop R packages, see the
following textbook by Hadley Wickham- <http://r-pkgs.had.co.nz/>

## Code of Conduct

Please note that the `rpkgtools` project is released with a [Contributor
Code of Conduct](CODE_OF_CONDUCT.md). By contributing to this project,
you agree to abide by its terms.
