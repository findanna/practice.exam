
<!-- README.md is generated from README.Rmd. Please edit that file -->

# practice.exam

<!-- badges: start -->
<!-- badges: end -->

The goal of practice.exam is to …

## Installation

You can install the development version of practice.exam from
[GitHub](https://github.com/) with:

``` r
install.packages("devtools")
#> Installing package into '/usr/local/lib/R/site-library'
#> (as 'lib' is unspecified)

devtools::install_github("findanna/practice.exam")
#> Downloading GitHub repo findanna/practice.exam@HEAD
#> 
#> * checking for file ‘/tmp/RtmpO4vXRD/remotes1cb6e5df15e4f/findanna-practice.exam-d2fc1a9/DESCRIPTION’ ... OK
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
#> # A tibble: 1,390 × 11
#>    Exercice `Dépenses/Recett…` `Investissemen…` `Imputation d’…` `Code chapitre`
#>       <dbl> <chr>              <chr>            <chr>            <chr>          
#>  1     2010 D                  F                N                011            
#>  2     2010 D                  F                N                011            
#>  3     2010 D                  F                N                011            
#>  4     2010 D                  F                N                011            
#>  5     2010 D                  F                N                011            
#>  6     2010 D                  F                N                011            
#>  7     2010 D                  F                N                011            
#>  8     2010 D                  F                N                011            
#>  9     2010 D                  F                N                011            
#> 10     2010 D                  F                N                011            
#> # … with 1,380 more rows, and 6 more variables: `Libellé chapitre` <chr>,
#> #   `Code sous-fonction` <chr>, `Libellé sous-fonction` <chr>,
#> #   `Code article` <chr>, `Libellé article` <chr>, Montant <chr>
#> 
#> $annee_2011.xlsx
#> # A tibble: 1,542 × 11
#>    Exercice `Dépenses/Recett…` `Investissemen…` `Imputation d’…` `Code chapitre`
#>       <dbl> <chr>              <chr>            <chr>            <chr>          
#>  1     2011 D                  F                N                011            
#>  2     2011 D                  F                N                011            
#>  3     2011 D                  F                N                011            
#>  4     2011 D                  F                N                011            
#>  5     2011 D                  F                N                011            
#>  6     2011 D                  F                N                011            
#>  7     2011 D                  F                N                011            
#>  8     2011 D                  F                N                011            
#>  9     2011 D                  F                N                011            
#> 10     2011 D                  F                N                011            
#> # … with 1,532 more rows, and 6 more variables: `Libellé chapitre` <chr>,
#> #   `Code sous-fonction` <chr>, `Libellé sous-fonction` <chr>,
#> #   `Code article` <chr>, `Libellé article` <chr>, Montant <chr>
#> 
#> $annee_2012.xlsx
#> # A tibble: 1,477 × 11
#>    Exercice `Dépenses/Recett…` `Investissemen…` `Imputation d’…` `Code chapitre`
#>       <dbl> <chr>              <chr>            <chr>            <chr>          
#>  1     2012 D                  F                N                011            
#>  2     2012 D                  F                N                011            
#>  3     2012 D                  F                N                011            
#>  4     2012 D                  F                N                011            
#>  5     2012 D                  F                N                011            
#>  6     2012 D                  F                N                011            
#>  7     2012 D                  F                N                011            
#>  8     2012 D                  F                N                011            
#>  9     2012 D                  F                N                011            
#> 10     2012 D                  F                N                011            
#> # … with 1,467 more rows, and 6 more variables: `Libellé chapitre` <chr>,
#> #   `Code sous-fonction` <chr>, `Libellé sous-fonction` <chr>,
#> #   `Code article` <chr>, `Libellé article` <chr>, Montant <chr>
#> 
#> $annee_2013.xlsx
#> # A tibble: 1,471 × 11
#>    Exercice `Dépenses/Recett…` `Investissemen…` `Imputation d’…` `Code chapitre`
#>       <dbl> <chr>              <chr>            <chr>            <chr>          
#>  1     2013 D                  F                N                011            
#>  2     2013 D                  F                N                011            
#>  3     2013 D                  F                N                011            
#>  4     2013 D                  F                N                011            
#>  5     2013 D                  F                N                011            
#>  6     2013 D                  F                N                011            
#>  7     2013 D                  F                N                011            
#>  8     2013 D                  F                N                011            
#>  9     2013 D                  F                N                011            
#> 10     2013 D                  F                N                011            
#> # … with 1,461 more rows, and 6 more variables: `Libellé chapitre` <chr>,
#> #   `Code sous-fonction` <chr>, `Libellé sous-fonction` <chr>,
#> #   `Code article` <chr>, `Libellé article` <chr>, Montant <chr>
#> 
#> $annee_2014.xlsx
#> # A tibble: 1,489 × 11
#>    Exercice `Dépenses/Recett…` `Investissemen…` `Imputation d’…` `Code chapitre`
#>       <dbl> <chr>              <chr>            <chr>            <chr>          
#>  1     2014 D                  F                N                011            
#>  2     2014 D                  F                N                011            
#>  3     2014 D                  F                N                011            
#>  4     2014 D                  F                N                011            
#>  5     2014 D                  F                N                011            
#>  6     2014 D                  F                N                011            
#>  7     2014 D                  F                N                011            
#>  8     2014 D                  F                N                011            
#>  9     2014 D                  F                N                011            
#> 10     2014 D                  F                N                011            
#> # … with 1,479 more rows, and 6 more variables: `Libellé chapitre` <chr>,
#> #   `Code sous-fonction` <chr>, `Libellé sous-fonction` <chr>,
#> #   `Code article` <chr>, `Libellé article` <chr>, Montant <chr>
#> 
#> $annee_2015.xlsx
#> # A tibble: 1,490 × 11
#>    Exercice `Dépenses/Recett…` `Investissemen…` `Imputation d’…` `Code chapitre`
#>       <dbl> <chr>              <chr>            <chr>            <chr>          
#>  1     2015 D                  F                N                011            
#>  2     2015 D                  F                N                011            
#>  3     2015 D                  F                N                011            
#>  4     2015 D                  F                N                011            
#>  5     2015 D                  F                N                011            
#>  6     2015 D                  F                N                011            
#>  7     2015 D                  F                N                011            
#>  8     2015 D                  F                N                011            
#>  9     2015 D                  F                N                011            
#> 10     2015 D                  F                N                011            
#> # … with 1,480 more rows, and 6 more variables: `Libellé chapitre` <chr>,
#> #   `Code sous-fonction` <chr>, `Libellé sous-fonction` <chr>,
#> #   `Code article` <chr>, `Libellé article` <chr>, Montant <chr>
#> 
#> $annee_2016.xlsx
#> # A tibble: 1,493 × 11
#>    Exercice `Dépenses/Recett…` `Investissemen…` `Imputation d’…` `Code chapitre`
#>       <dbl> <chr>              <chr>            <chr>            <chr>          
#>  1     2016 D                  N                F                011            
#>  2     2016 D                  N                F                011            
#>  3     2016 D                  N                F                011            
#>  4     2016 D                  N                F                011            
#>  5     2016 D                  N                F                011            
#>  6     2016 D                  N                F                011            
#>  7     2016 D                  N                F                011            
#>  8     2016 D                  N                F                011            
#>  9     2016 D                  N                F                011            
#> 10     2016 D                  N                F                011            
#> # … with 1,483 more rows, and 6 more variables: `Libellé chapitre` <chr>,
#> #   `Code sous-fonction` <chr>, `Libellé sous-fonction` <chr>,
#> #   `Code article` <chr>, `Libellé article` <chr>, Montant <chr>
#> 
#> $annee_2017.xlsx
#> # A tibble: 1,476 × 11
#>    Exercice `Dépenses/Recett…` `Imputation d’…` `Investissemen…` `Code chapitre`
#>       <dbl> <chr>              <chr>            <chr>            <chr>          
#>  1     2017 D                  N                F                012            
#>  2     2017 D                  N                F                012            
#>  3     2017 D                  N                F                012            
#>  4     2017 D                  N                F                012            
#>  5     2017 D                  N                F                012            
#>  6     2017 D                  N                F                012            
#>  7     2017 D                  N                F                012            
#>  8     2017 D                  N                F                012            
#>  9     2017 D                  N                F                012            
#> 10     2017 D                  N                F                012            
#> # … with 1,466 more rows, and 6 more variables: `Libellé chapitre` <chr>,
#> #   `Code sous-fonction` <chr>, `Libellé sous-fonction` <chr>,
#> #   `Code article` <chr>, `Libellé article` <chr>, Montant <chr>
#> 
#> $annee_2018.xlsx
#> NULL
```
