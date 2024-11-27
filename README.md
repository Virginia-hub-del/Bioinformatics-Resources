# **Bioinformatics Resources: Introduction - RNA-seq Analysis of Invasive Breast Cancer**

**Analysis of RNA-seq data from Breast Invasive Carcinoma to identify potential biomarkers.**  
Tools used: `biomaRt`, `edgeR`, `clusterProfiler` for data normalization, differential gene expression, and gene set enrichment with visualizations (volcano plots, heatmaps).

## **Overview**

This project focuses on RNA-seq analysis of invasive breast cancer using data from **TCGA (The Cancer Genome Atlas)**. The goal is to identify potential biomarkers for breast cancer by performing:
- **Differential gene expression analysis**
- **Gene set enrichment analysis** (Gene Ontology and KEGG)
- **Transcription factor analysis**

## **Key Features**

- **Data filtering and preprocessing**:  
  Cleaning and normalizing RNA-seq data.
  
- **Differential expression analysis**:  
  Using packages like `edgeR` to identify genes differentially expressed between cancer and normal tissues.
  
- **Visualization**:  
  Volcano plots, heatmaps, and other visualizations to explore gene expression patterns.
  
- **Gene set enrichment analysis**:  
  Performing **GO (Gene Ontology)** and **KEGG pathway enrichment** to identify biological processes associated with the differentially expressed genes.
  
- **Transcription factor analysis**:  
  Using `PWMEnrich` to identify transcription factor motifs in gene promoters.

## **Technologies Used**

- **R** and **Bioconductor** packages:
  - `biomaRt`
  - `edgeR`
  - `clusterProfiler`
  - `PWMEnrich`
  
- **Visualization**:  
  `ggplot2`, `heatmap` packages for data visualization.
  
- **Data Source**:  
  TCGA RNA-seq data for invasive breast cancer.

## **Requirements**

Before running the scripts, ensure that you have the following installed:

- **R** (version 4.0 or higher)
- The required R packages, which can be installed via the following commands:

```r
install.packages(c("ggplot2", "edgeR"))
BiocManager::install(c("biomaRt", "clusterProfiler", "PWMEnrich"))
```

## **Project Documentation**
For more details, please refer to the project documentation available in the repository:
  
[Bioinformatics Resources Project - PDF](Bioinformatics_Resources_Project.pdf)
