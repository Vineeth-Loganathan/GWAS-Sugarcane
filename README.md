# Genome-Wide Association Study (GWAS) Analysis

This repository contains the workflow, data, and scripts used to conduct a comprehensive Genome-Wide Association Study (GWAS) on sugarcane varieties. The project integrates advanced bioinformatics tools and statistical methods to explore genetic markers associated with key agronomic traits.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Methods](#methods)
- [Key Features](#key-features)
- [Visualizations](#visualizations)

## Overview

Sugarcane is a complex polyploid crop with significant economic importance. This study leverages genotypic and phenotypic data to identify SNPs and candidate genes associated with yield traits, providing insights to support marker-assisted breeding programs. The results were validated under field conditions over three years.

## Dataset
- **Genotypic Data**: 58,000 SNP markers derived from the Axiom Sugarcane 100K SNP array.
- **Phenotypic Data**: 6 traits including:
  - CANE_HEIGHT
  - CANE_WIDTH
  - SCW
  - INTERNODES
  - NMC
  - CANE_YIELD
  
## Methods
1. **BLUP Generation**:
   - Best Linear Unbiased Predictors (BLUPs) were calculated for phenotypic traits to account for environmental variation.

2. **GWAS Pipeline**:
   - Linear regression models used to assess SNP-trait associations.
   - Extracted coefficients and p-values for interpretation.

3. **Marker Alignment**:
   - Aligned SNPs using the *Sorghum genome* as reference genome.

4. **Functional Annotation**:
   - Integrated SNP annotations with publicly available genomic resources.

## Key Features
- **Reproducible Workflow**: Streamlined and well-documented scripts for ease of use.
- **High-Quality Data**: Integration of multi-year field evaluations to enhance reliability.
- **Statistical Insights**: Comprehensive extraction of SNP-trait association metrics.
- **Visualization**: Clear and informative Manhattan plots and coefficient plots for interpretation.

## Visualizations
- **Manhattan Plots**: Highlight significant SNPs for each trait.
- **Coefficient Plots**: Represent the magnitude and direction of SNP effects.
