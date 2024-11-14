# Bioinformatics Resources: Introduction - RNA-seq Analysis of Invasive Breast Cancer
[Download the Project PDF](Bioinformatics_Resources_project.pdf)
## Overview

This project focuses on RNA-seq analysis of invasive breast cancer using data from TCGA (The Cancer Genome Atlas). The goal is to identify potential biomarkers for breast cancer by performing differential gene expression analysis, gene set enrichment analysis (Gene Ontology and KEGG), and transcription factor analysis.

### Key Features:
- **Data filtering and preprocessing**: Cleaning and normalizing RNA-seq data.
- **Differential expression analysis**: Using packages like edgeR to identify genes differentially expressed between cancer and normal tissues.
- **Visualization**: Volcano plots, heatmaps, and other visualizations to explore gene expression patterns.
- **Gene set enrichment analysis**: Performing GO (Gene Ontology) and KEGG pathway enrichment to identify biological processes associated with the differentially expressed genes.
- **Transcription factor analysis**: Using PWMEnrich to identify transcription factor motifs in gene promoters.

## Technologies Used
- **R** and **Bioconductor** packages:
  - `biomaRt`
  - `edgeR`
  - `clusterProfiler`
  - `PWMEnrich`
- **Visualization**: `ggplot2`, `heatmap` packages for visualizations
- **Data Source**: TCGA RNA-seq data for invasive breast cancer

## Requirements

Before running the scripts, ensure that you have the following installed:

- R (version 4.0 or higher)
- The required R packages, which can be installed via the following commands:

```r
install.packages(c("ggplot2", "edgeR"))
BiocManager::install(c("biomaRt", "clusterProfiler", "PWMEnrich"))
'''r
