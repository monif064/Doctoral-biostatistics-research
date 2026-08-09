# Doctoral Biostatistics Research

This repository presents selected code and supporting materials from my doctoral research in biostatistics. The main focus of the research is the development of statistical methods for **extreme phenotype sampling**, with applications to genetic association studies.

## Research Overview

Extreme phenotype sampling selects individuals with unusually high or low values of a trait for further study. My doctoral research examined statistical methods designed for this sampling approach, including situations involving:

- Continuous and binary traits
- Missing genotype information
- Population structure
- Linear mixed models
- Expectation-Maximization algorithms
- Genetic association testing
- Simulation-based evaluation of statistical methods.

## Repository Contents

The repository will contain selected and reorganized materials from three main areas of my doctoral research:

### 1. Mixed-Model Approaches for Population Substructure

R code and simulation studies supporting the comparison of mixed-model-based approaches for correcting population substructure, with applications to genetic association analysis under extreme phenotype sampling.

This work relates to my first doctoral publication:

*Comparison of mixed model based approaches for correcting for population substructure with application to extreme phenotype sampling.*

### 2. Linear Mixed Model Development for Extreme Phenotype Sampling

Development and evaluation of a linear mixed model method for correcting population structure in studies using extreme phenotype sampling (EPS). This work explored likelihood-based estimation and inference procedures, including the Expectation-Maximization algorithm, Monte Carlo methods, likelihood ratio tests, and Wald tests.

The project includes R code and simulation studies used to assess the statistical properties and performance of the proposed method.

### 3. Continuing Research and Method Development

Ongoing work extending the methods and computational approaches developed during my doctoral research. This section will include selected methodological developments, simulation studies, research code, and reproducible workflows as they become ready for public sharing.

### 4. Research Computing Workflows

Selected R functions, high-performance computing scripts, simulation workflows, and reproducibility documentation used throughout the doctoral research.

## Planned Structure

```text
Doctoral-biostatistics-research/
├── R/
│   ├── functions/
│   └── utilities/
projects/
├── population-substructure-model-comparison/
├── linear-mixed-model-development-eps/
└── continuing-research/
├── hpc/
│   └── slurm/
├── publications/
├── supplementary-materials/
├── figures/
└── documentation/
