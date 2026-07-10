# ALS WGCNA Analysis

This repository contains a Weighted Gene Co-expression Network Analysis (WGCNA) workflow applied to an ALS transcriptomics dataset.

## Overview

WGCNA identifies groups of genes with similar expression patterns and relates gene modules to biological traits.

This analysis includes:

- Data preprocessing and filtering
- Sample quality control
- Soft-threshold selection
- Network construction
- Module identification
- Module-trait correlation analysis
- Cytoscape visualization

## Files

- `WGCNA_ALS.Rmd` — R Markdown workflow
- `WGCNA_ALS.html` — knitted HTML report
- `figures/` — generated figures

## Report

Open the knitted report:

`WGCNA_ALS.html`

## Software

- R 4.4.1
- WGCNA
- DESeq2
- tidyverse
- igraph
- ggplot2