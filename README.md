<!-- README.md is generated from README.Rmd. Please edit that file -->
VaccCompData
============

VaccCompData provides the raw data and the scripts used to process them for the paper 'A comparison of antigen-specific T cell responses induced by six novel tuberculosis vaccine candidates'. Its installation is required to run the analysis script in the package VaccComp.

To install VaccCompData, run:

``` r
devtools::install_github("MiguelRodo/VaccCompData", build_vignettes = TRUE)
```

The raw .xlsx and .csv files are contained in the folder extdata. The R code used to create it is available in the folder dataprep. Within dataprep, the file Makefile.R will load the raw data and run the corresponding R scripts to recompile the data used for the analysis from scratch. For details of the order of running the scripts and their output, as well as the raw data files themselves, see the vignette VaccCompData, which can be accessed by running:

``` r
vignette("VaccCompData")
```
