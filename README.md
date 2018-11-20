
<!-- README.md is generated from README.Rmd. Please edit that file -->

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
#> v devtools     2.0.1          v testthat     2.0.1     
#> v covr         3.2.1          v spelling     1.2       
#> v lintr        1.0.3          v roxygen2     6.1.1     
#> v goodpractice 1.0.2          v styler       1.0.2.9000
#> v pkgdown      1.1.0.9000
#> -- Conflicts -------------------------------------------------------------------------------------- devtoolverse_conflicts() --
#> x pkgdown::build_site()           masks devtools::build_site()
#> x lintr::lint()                   masks devtools::lint()
#> x devtoolverse::package_version() masks base::package_version()
#> x testthat::setup()               masks devtools::setup()
#> x testthat::test_file()           masks devtools::test_file()
#> x usethis::use_appveyor()         masks devtools::use_appveyor()
#> x usethis::use_build_ignore()     masks devtools::use_build_ignore()
#> x usethis::use_code_of_conduct()  masks devtools::use_code_of_conduct()
#> x usethis::use_coverage()         masks devtools::use_coverage()
#> x usethis::use_cran_badge()       masks devtools::use_cran_badge()
#> x usethis::use_cran_comments()    masks devtools::use_cran_comments()
#> x usethis::use_data()             masks devtools::use_data()
#> x usethis::use_data_raw()         masks devtools::use_data_raw()
#> x usethis::use_dev_version()      masks devtools::use_dev_version()
#> x usethis::use_git()              masks devtools::use_git()
#> x usethis::use_git_hook()         masks devtools::use_git_hook()
#> x usethis::use_github()           masks devtools::use_github()
#> x usethis::use_github_links()     masks devtools::use_github_links()
#> x usethis::use_gpl3_license()     masks devtools::use_gpl3_license()
#> x usethis::use_mit_license()      masks devtools::use_mit_license()
#> x usethis::use_news_md()          masks devtools::use_news_md()
#> x usethis::use_package()          masks devtools::use_package()
#> x usethis::use_package_doc()      masks devtools::use_package_doc()
#> x usethis::use_rcpp()             masks devtools::use_rcpp()
#> x usethis::use_readme_md()        masks devtools::use_readme_md()
#> x usethis::use_readme_rmd()       masks devtools::use_readme_rmd()
#> x usethis::use_revdep()           masks devtools::use_revdep()
#> x usethis::use_rstudio()          masks devtools::use_rstudio()
#> x usethis::use_test()             masks devtools::use_test()
#> x usethis::use_testthat()         masks devtools::use_testthat()
#> x usethis::use_travis()           masks devtools::use_travis()
#> x usethis::use_vignette()         masks devtools::use_vignette()
#> 
#> Attaching package: 'devtoolverse'
#> The following object is masked from 'package:base':
#> 
#>     package_version
```
