# Antimicrobial Susceptibility Analysis Pipeline

This repository contains a reproducible data analysis workflow for processing and visualizing antimicrobial susceptibility testing (AST) data from bacterial isolates.

The scripts and notebook in this project were used to generate statistical summaries and visualizations for the study:

**"Linking Genomic Landscape to Disease Mechanism: Core Genetic Factors Underlying Pathogenesis and Antimicrobial Resistance in Diarrheal Pathogens"**
Preprint Link: 
https://www.biorxiv.org/content/10.1101/2025.08.31.673274v1

---

## 📊 Project Overview

This pipeline performs the following tasks:

1. Loads raw AST data from Excel files with hierarchical headers
2. Cleans and restructures the dataset
3. Converts wide-format data into tidy long format
4. Extracts antibiotic and measurement information
5. Generates analysis-ready structured tables
6. Produces publication-quality visualizations

---

## 📁 Repository Structure

├── notebook/
│ └── AST_Analysis.ipynb # Main analysis notebook
├── data/
│ └── AST_Data.xlsx # Input dataset (not included)
├── output/
│ └── figures/ # Generated plots
└── README.md


## Requirements

Python 3.9+
pandas
plotly

## Note

Raw data are not included due to publication policy.
