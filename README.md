# BhoodscanR & scider: Spatial downstream analysis workshop

## Overview

This workshop will introduce two Bioconductor packages, hoodscanR and scider,
for performing downstream analysis on spatial transcriptomics data to identify
cell neighbourhoods and model density.
We apply these packages to analyse a publicly available Xenium dataset to answer
different biological questions

The workshop will be organised into two broad sections:
* Conducting neighborhood analysis using hoodscanR
* Conducting density analysis using scider

Detailed material can be found [here](https://pololab.github.io/SpatialAnalysisWorkshop/).

## Pre-requisites 

The workshop is aimed at researchers who are interested in in-depth analysis of spatial transcriptomics data. 
Basic R knowledge is assumed - this is not an introduction to R course. 
If you are not familiar with the R statistical programming language it is 
strongly suggested that you work through an introductory R course before you attend this workshop.

## _R_ packages used

The following key R packages will be used: 

* `hoodscanR`
* `scider`
* `Seurat`
* `edgeR`
* `tidyverse`

## Time outline

| Activity                                                        | Time |
|-----------------------------------------------------------------|------|
| Introduction & setup                                            |5-10m |
| Part A. Local neighborhoods with hoodscanR                      |35-40m|
| Part B. Cell‑type density modelling with scider                 |35-40m|
| Part C. Useful utilities for Python tools                       | 5m   |
| Q & A                                                           | 5m   |


## Workshop goals and objectives

### Learning goals

 - Learn how to use hoodscanR to perform neighborhood analysis with spatial transcriptomics data.
 - Learn how to use scider to conduct density modelling with spatial transcriptomics data.

## Workshop package installation 

### Guide

This is necessary in order to reproduce the code shown in the workshop. 
The workshop is designed for R `4.5.1+` and Bioconductor `3.22+`, and it can be installed via GitHub with the following command.

Bioconductor can be installed by the following codes if you haven't installed:

```
install.packages("BiocManager")

BiocManager::install()
```

To install this workflow package:

```
install.packages('remotes')

# Install workshop package
remotes::install_github("pololab/SpatialAnalysisWorkshop", build_vignettes = FALSE)
```
