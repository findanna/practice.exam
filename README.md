
<!-- README.md is generated from README.Rmd. Please edit that file -->

# practice.exam

<!-- badges: start -->
<!-- badges: end -->

The goal of practice.exam is to …

## Installation

You can install the development version of practice.exam from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")

devtools::install_github("findanna/practice.exam")
#> Downloading GitHub repo findanna/practice.exam@HEAD
#> cli    (3.1.0  -> 3.3.0) [CRAN]
#> glue   (1.6.0  -> 1.6.2) [CRAN]
#> vctrs  (0.3.8  -> 0.4.1) [CRAN]
#> rlang  (0.4.12 -> 1.0.2) [CRAN]
#> crayon (1.4.2  -> 1.5.1) [CRAN]
#> pillar (1.6.4  -> 1.7.0) [CRAN]
#> fansi  (1.0.0  -> 1.0.3) [CRAN]
#> tibble (3.1.6  -> 3.1.7) [CRAN]
#> readxl (1.3.1  -> 1.4.0) [CRAN]
#> Installing 9 packages: cli, glue, vctrs, rlang, crayon, pillar, fansi, tibble, readxl
#> Installing packages into '/usr/local/lib/R/site-library'
#> (as 'lib' is unspecified)
#> * checking for file ‘/tmp/RtmphN8aYo/remotes1ad676c6d80c7/findanna-practice.exam-f2e5e0b/DESCRIPTION’ ... OK
#> * preparing ‘practice.exam’:
#> * checking DESCRIPTION meta-information ... OK
#> * checking for LF line-endings in source and make files and shell scripts
#> * checking for empty or unneeded directories
#> * building ‘practice.exam_0.0.0.9000.tar.gz’
#> Installing package into '/usr/local/lib/R/site-library'
#> (as 'lib' is unspecified)
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(practice.exam)
multi_read_excel(folder = "inst/")
#> $annee_2009.xlsx
#> NULL
#> 
#> $annee_2010.xlsx
#> NULL
#> 
#> $annee_2011.xlsx
#> NULL
#> 
#> $annee_2012.xlsx
#> NULL
#> 
#> $annee_2013.xlsx
#> NULL
#> 
#> $annee_2014.xlsx
#> NULL
#> 
#> $annee_2015.xlsx
#> NULL
#> 
#> $annee_2016.xlsx
#> NULL
#> 
#> $annee_2017.xlsx
#> NULL
#> 
#> $annee_2018.xlsx
#> NULL
```
