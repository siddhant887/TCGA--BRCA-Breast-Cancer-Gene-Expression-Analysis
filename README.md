## Project Overview

This project analyzes gene expression data from The Cancer Genome Atlas Breast Invasive Carcinoma (TCGA-BRCA) dataset.

The main aim of the project is to compare gene expression between breast cancer tumor samples and normal breast tissue samples and identify genes and biological pathways associated with breast cancer.

## Analysis Workflow

The project follows this workflow:

*TCGA-BRCA data → Tumor vs Normal comparison → Differential Gene Expression → PCA → Volcano Plot → Pathway Enrichment → Gene Signature Analysis*

## 1. Tumor vs Normal

Gene expression profiles from breast cancer tumor samples were compared with normal breast tissue samples.

This comparison helps identify genes whose expression changes between cancerous and normal tissue.

## 2. Differential Gene Expression Analysis

Differential expression analysis was performed using *DESeq2*.

The analysis identifies genes that show significant differences in expression between tumor and normal samples.

Important measurements include:

- Log2 fold change
- p-value
- Adjusted p-value (padj)
- Base mean expression

## 3. PCA Analysis

Principal Component Analysis (PCA) was used to visualize the overall expression patterns of the samples.

The PCA plot helps evaluate whether tumor and normal samples show distinct expression patterns.

## 4. Volcano Plot

A volcano plot was generated to visualize differential gene expression.

It combines:

- Fold change
- Statistical significance

This helps identify strongly upregulated and downregulated genes.

## 5. Significant Genes

Significant differentially expressed genes were identified from the differential expression results using statistical significance criteria.

These genes were subsequently used for downstream biological interpretation.

## 6. Pathway Enrichment Analysis

Pathway enrichment analysis was performed using the significant gene results.

FGSEA was used to investigate biological pathways associated with the observed gene-expression changes.

## 7. Gene Signature Analysis

A gene signature analysis was performed to examine the expression patterns of selected genes associated with the analysis.

## Results

The repository contains the recovered analysis results and visualizations, including:

- Differential expression results
- Significant genes
- FGSEA pathway results
- Pathway information
- Volcano plot data
- Sample information
- PCA plot
- Volcano plot
- Pathway enrichment visualization
- Gene signature visualization

## Tools and Technologies

- R
- DESeq2
- FGSEA
- TCGA-BRCA data
- R data objects (.rds)

## Project Significance

This analysis demonstrates a bioinformatics workflow for investigating gene-expression differences in breast cancer and connecting differentially expressed genes with biological pathways.

## Repository Contents

The repository contains the analysis results and visualizations generated during the project.
