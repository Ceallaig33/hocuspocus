
## TEST

# hocuspocus

hocuspocus provides an easy-to-use and intuitive workflow for basic analysis of 
single-cell RNA-Seq data.  It combines custom functions with functions from 
available packages.  Particular emphasis is placed on data presentation and 
visualization, with a variety of options for controlling the appearance of 
plots.  Currently, tools include selection of important expressed genes based on
variance and PCA, heatmaps with color bars, blot plots, 1D, 2D, and 3D PCA 
plots, clustering analysis, gap statistic caclulation, and all of the temporal 
ordering and differential expression analysis tools from monocle.

## First installation
To install hocuspocus and run it for the first time, open a new R or RStudio
session and type the following commands:

```
install.packages("devtools")
source("https://bioconductor.org/biocLite.R")
biocLite("sva")
devtools::install_github("satijalab/seurat")
devtools::install_github("joeburns06/hocuspocus")
library(hocuspocus)
```

## Subsequent R sessions
After this initial installation, you should only need the following command to 
load and attach hocuspocus in subsequent R sessions:

```
library(hocuspocus)
```

## Getting the latest version of hocuspocus
To obtain the latest version of hocuspocus, type the following commands:

```
devtools::install_github("joeburns06/hocuspocus")
library(hocuspocus)
```

