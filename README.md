# Quality control for the target decoy approach for peptide identification

The compagnon website of this repo can be found on [https://statomics.github.io/TargetDecoyPaper/](https://statomics.github.io/TargetDecoyPaper/)

## Abstract

Reliable peptide identification is key in mass spectrometry (MS) based proteomics. To  this end, the target-decoy approach (TDA) has become the cornerstone for extracting a set of reliable peptide-to-spectrum matches (PSMs) that will be used in downstream analysis. Indeed, TDA is now the default method to estimate the false discovery rate (FDR) for a given set of PSMs, and users typically view it as a universal solution for assessing the FDR in the peptide identification step. However, the TDA also relies on a minimal set of assumptions, which are typically never verified in practice. We argue that a violation of these assumptions can lead to poor FDR control, which can be detrimental to  any downstream data analysis. We here therefore first clearly spell out these TDA assumptions, and introduce TargetDecoy, a Bioconductor package with all the necessary functionality to control the TDA quality and its underlying assumptions for a given set of PSMs.

***
  
## Availability of data
  
  The datasets required to reproduce all results that are displayed in this publication (including supplementary materials) are available at Zenodo. This includes both the raw data and intermediate results. Note that at the top of each analysis script it is indicated which dataset is required as input for the script; it may thus not be necessary to download all datasets from [Zenodo](https://doi.org/10.5281/zenodo.730). For easily reproducing our analyses, place the downloaded data in the `Data` folder of your local clone of this repository.

***
  
## Analyses & Scripts
  
To reproduce the results that are displayed in this publication, proceed as follows:
  
1. Make a local clone of this Github repository
2. Open the selected R scripts (.Rmd) in the root of this repository.
4. Run the analyses - the figures will automatically be stored in the figs folder . 

