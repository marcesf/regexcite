
<!-- README.md is generated from README.Rmd. Please edit that file -->

# regexcite

<!-- badges: start -->
<!-- badges: end -->

The goal of regexcite is to …

## Installation

You can install the development version of regexcite from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("marcesf/regexcite")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(regexcite)
str_split_one("a,b,c", ",", n = 2)
#> [1] "a"   "b,c"
```
