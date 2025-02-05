
<!-- README.md is generated from README.Rmd. Please edit that file -->

# pkgdown <img src="man/figures/logo.png" align="right" alt="" width="120" />

<!-- badges: start -->

[![Lifecycle:
maturing](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)
<a href="https://cran.r-project.org/package=pkgdown" class="pkgdown-release"><img src="https://www.r-pkg.org/badges/version/pkgdown" alt="CRAN Status" /></a>
<a href="https://github.com/r-lib/pkgdown/actions" class="pkgdown-devel"><img src="https://github.com/r-lib/pkgdown/workflows/R-CMD-check/badge.svg" alt="R-CMD-check" /></a>
[![Codecov test
coverage](https://codecov.io/gh/r-lib/pkgdown/branch/main/graph/badge.svg)](https://codecov.io/gh/r-lib/pkgdown?branch=main)
<!-- badges: end -->

pkgdown is designed to make it quick and easy to build a website for
your package. You can see pkgdown in action at
<https://pkgdown.r-lib.org>: this is the output of pkgdown applied to
the latest version of pkgdown. Learn more in `vignette("pkgdown")` or
`?build_site`.

## Installation

<div class=".pkgdown-release">

``` r
# Install released version from CRAN
install.packages("pkgdown")
```

</div>

<div class=".pkgdown-devel">

``` r
# Install development version from GitHub
devtools::install_github("r-lib/pkgdown")
```

</div>

## Usage

Get started with [usethis](https://usethis.r-lib.org/):

``` r
# Run once to configure your package to use pkgdown
usethis::use_pkgdown()
```

Use pkgdown to update your website:

``` r
# Run to build the website
pkgdown::build_site()
```

This generates a `docs/` directory containing a website. Your
`README.md` becomes the homepage, documentation in `man/` generates a
function reference, and vignettes will be rendered into `articles/`.
Read `vignette("pkgdown")` for more details and to learn how to
customise your site.

If you are using GitHub, the easiest way to make this your package
website is to check into git, then go to settings for your repo and make
sure that the **GitHub pages** source is set to “gh-pages branch /(root)
folder”. Be sure to update the URL on your github repository homepage so
others can easily navigate to your new site.

## In the wild

At last count, pkgdown is used [by over 6,000
packages](https://github.com/search?q=filename%3Apkgdown.yml+path%3A%2F&type=Code).

Here are a few examples created by contributors to pkgdown:

-   [bayesplot](http://mc-stan.org/bayesplot/index.html)
    ([source](https://github.com/stan-dev/bayesplot/tree/gh-pages)):
    plotting functions for posterior analysis, model checking, and MCMC
    diagnostics.

-   [valr](https://rnabioco.github.io/valr/)
    ([source](https://github.com/rnabioco/valr)): read and manipulate
    genome intervals and signals.

-   [mkin](http://jranke.github.io/mkin/)
    ([source](https://github.com/jranke/mkin)): calculation routines
    based on the FOCUS Kinetics Report

-   [NMF](http://renozao.github.io/NMF/master/index.html)
    ([source](https://github.com/renozao/NMF)): a framework to perform
    non-negative matrix factorization (NMF).

Comparing the source and output of these sites is a great way to learn
new pkgdown techniques.

## Code of conduct

Please note that this project is released with a [Contributor Code of
Conduct](https://pkgdown.r-lib.org/CODE_OF_CONDUCT.html). By
participating in this project you agree to abide by its terms.
