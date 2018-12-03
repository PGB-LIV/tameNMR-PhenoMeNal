# Tools for Analysis of MEtabolomic NMR (tameNMR)

## This version is meant for the PhenoMenal project

tameNMR is a suite of tools for processing and analysis of NMR data from metabolomics
experiments. It is designed as a set of command line programs to be used
as standalone tools or for design of automated workflows in Galaxy
(galaxyproject.org) framework.


## Structure
The package includes the following tools:

1. Import - Import of NMR data (from Bruker raw files)
    * Bruker to csv
2. ProcessSpectra
    * Normalisation
    * Peak Picking
    * Spectra alignment
    * Preparation of pattern files for binning
    * Binning
3. ProcessData
    * Scaling
    * Normalisation of data tables
    * Data transformations
    * Make factor template (for grouping observations)
4. Stats - univariate and multivariate statistics
    * t-tests
    * one-way ANOVA
    * Principal component analysis (PCA)
    * Partial least squares discriminant analysis (PLS-DA)
5. Plots - various plotting tools for:
    * Raw NMR spectra
    * Quantiles of spectra
    * Significant bins (p-values from t-tests of ANOVA)
    * Significant bins (mean value comparison)

