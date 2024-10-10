
<!-- README.md is generated from README.Rmd. Please edit that file -->

# genomeverse <a href="https://mskcc-epi-bio.github.io/genomeverse/"><img src="man/figures/logo.png" align="right" height="120" alt="genomeverse website" /></a>

<!-- badges: start -->
<!-- badges: end -->

genomeverse is a collection of R packages that are designed to work
together seamlessly to create reproducible clinico-genomic analysis
pipelines

## Installation

You can install the development version of genomeverse from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("MSKCC-Epi-Bio/genomeverse")
```

## Usage

`library(genomeverse)` will load the core genomeverse packages:

- [cbioportalR](https://www.karissawhiting.com/cbioportalR/), for
  pulling data from cBioPortal.
- [oncokbR](https://www.karissawhiting.com/oncokbR/), for oncoKB
  annotation fo data.
- [gnomeR](https://mskcc-epi-bio.github.io/gnomeR/), for processing raw
  mutation, CNA and fusion files.

You also get a condensed summary of conflicts with other packages you
have loaded:

``` r
library(genomeverse)
#> ── Attaching packages ──────────────────────────────── genomeverse 0.0.0.9001 ──
#> ✔ cbioportalR 1.1.0          ✔ oncokbR     0.0.0.9001
#> ✔ gnomeR      1.2.0.9004
```

## Code of Conduct

Please note that the tidyverse project is released with a [Contributor
Code of Conduct](https://tidyverse.tidyverse.org/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
