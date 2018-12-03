# Tools for Analysis of MEtabolomic NMR (tameNMR)

## This version is meant for the PhenoMenal project ([link](http://phenomenal-h2020.eu/home/))

tameNMR is a suite of tools for processing and analysis of NMR data from metabolomics
experiments. It is designed as a set of command line programs to be used
as standalone tools or for design of automated workflows in Galaxy
(galaxyproject.org) framework.


## Structure
The package includes the following tools:

1. ProcessSpectra
    * Normalisation
    * Peak Picking
    * Spectra alignment
    * Preparation of pattern files for binning
    * Binning
2. ProcessData
    * Scaling
    * Normalisation of data tables
    * Data transformations
    * Make factor template (for grouping observations)
3. Stats - univariate and multivariate statistics
    * t-tests
    * one-way ANOVA
    * Principal component analysis (PCA)
    * Partial least squares discriminant analysis (PLS-DA)
4. Plots - various plotting tools for:
    * Raw NMR spectra
    * Quantiles of spectra
    * Significant bins (p-values from t-tests of ANOVA)
    * Significant bins (mean value comparison)

