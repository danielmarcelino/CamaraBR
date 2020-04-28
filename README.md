
<!-- README.md is generated from README.Rmd. Please edit that file -->

# CamaraBR <img src="inst/figures/CamaraBR-logo.png" width="240px" align="right" />

[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![Build
Status](https://travis-ci.org/danielmarcelino/CamaraBR.svg?branch=master)](https://travis-ci.org/danielmarcelino/CamaraBR)
![CRAN Version](https://www.r-pkg.org/badges/version/CamaraBR)
![License](https://img.shields.io/badge/license-MIT-blueviolet.svg?style=flat)

## R package for accessing the Brazilian Chamber of Deputies RESTful API

## Installation

To get the current development version from Github:

``` r
## install devtools package if it's not already
if (!requireNamespace("devtools", quietly = TRUE)) {
  install.packages("devtools")
}
## install dev version of CamaraBR from github
devtools::install_github("danielmarcelino/CamaraBR")
## load SenadoBR package
library(CamaraBR)
```

## Usage