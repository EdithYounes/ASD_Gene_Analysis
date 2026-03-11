# Autism Gene Expression Analysis using Machine Learning

![Python](https://img.shields.io/badge/python-3.11-blue)
![Jupyter](https://img.shields.io/badge/jupyter-notebook-orange)
![License](https://img.shields.io/badge/license-MIT-green)

![Summary Figure](figures/summary_figure_all_panels.png)

This repository contains a computational project analyzing autism spectrum disorder (ASD) gene expression profiles using machine learning and statistical methods. It demonstrates my ability to combine **biology, data science, and computational modeling** — skills highly relevant for a Master's in Biomedical Engineering.  

---

## Motivation

I am a Biology graduate with a strong interest in **computational biology and biomedical engineering**. This project reflects my passion for combining **molecular biology, data science, and machine learning** to uncover patterns in complex biological datasets. By analyzing autism gene expression and identifying candidate genes using advanced ML techniques, I aim to develop skills that will contribute to translational biomedical research and future innovations in healthcare.  

---

## 🔬 Project Overview

- **Objective:** Identify ASD-associated genes and explore differential gene expression patterns between autism and control samples.  
- **Dataset:** Microarray gene expression dataset from [GEO: GSE18123](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE18123).  
- **Approach:**  
  - Data preprocessing and cleaning  
  - Selection of highly variable genes  
  - Standardization and dimensionality reduction (PCA)  
  - Classification using Random Forest  
  - Feature importance analysis  
  - Statistical significance analysis (t-test, volcano plot)  
  - Visualization of results with heatmaps, PCA plots, and summary figures  

---

## ⚙️ Project Structure

```txt
.
├── README.md
├── notebook.ipynb                # Full analysis notebook
├── figures/                      # Folder containing all figures
│   ├── summary_figure_all_panels.png
│   ├── pca_autism_samples.png
│   ├── confusion_matrix.png
│   ├── feature_importance_genes.png
│   ├── top20_genes_heatmap.png
│   ├── volcano_plot_autism.png
│   └── pca_animation.gif         # Optional PCA GIF
├── requirements.txt              # Minimal environment packages
└── LICENSE                       # MIT License
