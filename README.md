
<!-- badges: start -->

[![test-coverage](https://github.com/jamestsakalos/comspat/workflows/test-coverage/badge.svg)](https://github.com/jamestsakalos/comspat/actions)
[![Codecov test
coverage](https://codecov.io/gh/jamestsakalos/comspat/branch/master/graph/badge.svg)](https://app.codecov.io/gh/jamestsakalos/comspat?branch=master)
[![R-CMD-check](https://github.com/jamestsakalos/comspat/workflows/R-CMD-check/badge.svg)](https://github.com/jamestsakalos/comspat/actions)
<!-- badges: end -->

<!-- README.md is generated from README.Rmd. Please edit that file -->

# climenv

R functions for downloading, extracting, and plotting climatological
data as a function of user supplied multi and single geospatial polygon
and point data.

## Description

If you are a scientist seeking a convenient solution for downloading,
extracting , and plotting climatological data, consider exploring the
features of this package. It grants you access to three widely
recognised modelled data sets, namely WorldClim 2, CHELSA, and NASA’s
SRTM. It seamlessly handles both multi and single geospatial polygon and
point data, allowing you to extract outputs that can serve as covariates
in various ecological studies. It also allows you to visualise these
extractions using two common graphic options – the Walter-Lieth climate
diagram and the Holdridge life zone classification scheme. The last
option is a scheme of our own design which incorporates aspects of both
Walter-Leigh and Holdridge. The package’s user-friendly access and
extraction of globally recognisable data sets significantly enhance its
versatility and usability across a broad spectrum of applications.

For any questions, comments or bug reports please submit an issue here
on GitHub. Suggestions, ideas and references of new algorithms are
always welcome.

## News

- June-2023: Version 1.o.0

## Main functionalities

- Downloads climate data from two main sources;
  - CHELSA
  - WorldClim 2
- Downloads elevation data from two main sources;
  - get_data()
  - elevatr
- Extracts the data;
  - as raw data for points
  - as zonal statistics for a group of points or over a spatial extent
    (polygon)

## Installation from the source

You can install the released version of climenv from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("climenv")
```

And the development version from
[GitHub](https://github.com/jamestsakalos/climenv) with:

``` r
# install.packages("devtools")
devtools::install_github("jamestsakalos/climenv", build_vignettes = TRUE)
```

## Example

This is a basic example which shows you how to use the main climenv
function:

``` r
library(climenv)

#data("grid_random") #input data frame
```

The package vignette provides detailed explanation and demonstration on
the application of climenv.

## References

Juhász-Nagy, P. (1967). On association among plant populations I. *Acta
Biologica Debrecina*, 5, 43–56.

Juhász-Nagy, P. (1976). Spatial dependence of plant populations. Part 1.
Equivalence analysis (an outline for a new model). *Acta Botanica
Academiae Scientiarum Hungaricae*, 22, 61–78.

Juhász-Nagy, P. & Podani, J. (1983). Information theory methods for the
study of spatial processes and succession. *Vegetatio*, 51, 129–140.

Juhász-Nagy, P. (1984a). Notes on diversity. Part I. Introduction.
*Abstracta Botanica*, 8, 43–55.

Juhász-Nagy, P. (1984b). Spatial dependence of plant populations. Part
2. A family of new models. *Acta Botanica Hungarica*, 30, 363–402.

Juhász-Nagy, P. (1993). Notes on compositional diversity.
*Hydrobiologia*, 249, 173–182.
