# Autism Gene Expression Analysis Using Machine Learning

![Python](https://img.shields.io/badge/python-3.11-blue) 
![Jupyter](https://img.shields.io/badge/jupyter-notebook-orange) 
![License](https://img.shields.io/badge/license-MIT-green)

![Summary Figure](figures/summary_figure_all_panels.png)
*Summary figure combining PCA, top gene heatmap, volcano plot, and feature importance.*


**Author:** Edith Younes  

> **Project Pitch:** This project demonstrates my ability to integrate **biology, data science, and machine learning** by analyzing autism gene expression data and identifying candidate genes. It showcases skills directly relevant to computational and biomedical research, making it highly applicable for a Master’s in Biomedical Engineering.

---

## About Me & Motivation

I am a **Biology graduate** with a strong interest in **computational biology and biomedical engineering**. This project reflects my passion for combining **molecular biology, machine learning, and statistical analysis** to uncover patterns in complex biological datasets.  

By identifying candidate genes associated with autism, I aim to develop **computational and analytical skills that support translational biomedical research** and future innovations in healthcare.

---

## Project Overview

- **Objective:** Identify ASD-associated genes and explore differential gene expression patterns between autism and control samples.  
- **Dataset:** [GEO: GSE18123](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE18123) – microarray gene expression dataset.  
- **Approach:**  
  - Data preprocessing and cleaning  
  - Selection of top 5,000 most variable genes  
  - Standardization and dimensionality reduction (PCA)  
  - Classification using Random Forest  
  - Feature importance analysis  
  - Statistical significance analysis (t-test, volcano plot)  
  - Visualization with heatmaps, PCA plots, and summary figures  

---

## Project Structure

ASD_Gene_Analysis
- **README.md** – Project overview and instructions
- **ASD_analysis.ipynb** – Full analysis notebook
- **figures/** – Folder containing all figures
  - `summary_figure_all_panels.png`
  - `pca_autism_samples.png`
  - `confusion_matrix.png`
  - `feature_importance_genes.png`
  - `top20_genes_heatmap.png`
  - `volcano_plot_autism.png`
- **requirements.txt** – Minimal environment packages
- **LICENSE** – MIT License
---

## Methods & Analysis

- **Data Loading:** GEOparse to download and process GSE18123  
- **Label Assignment:** Classified samples as Autism (1) or Control (0)  
- **Gene Filtering:** Selected top 5,000 most variable genes  
- **Dimensionality Reduction:** PCA to visualize sample clustering  
- **Random Forest Classification:**  
  - 80%-20% train-test split  
  - Accuracy evaluation and confusion matrix  
  - Feature importance ranking of genes  
- **Statistical Analysis:** t-tests and volcano plots for significant genes  
- **Candidate Gene Detection:** Intersection of top ML genes with statistically significant genes  

---

## Key Results

- PCA shows **clear separation** between ASD and control samples  
- Random Forest achieved **strong classification performance** (accuracy details in notebook)  
- Top genes identified using both ML and statistical significance  
- Visualizations include heatmaps, volcano plots, and a **comprehensive summary figure**

---

## Future Work

- Extend analysis to **RNA-seq datasets** for higher resolution  
- Integrate **pathway and network analysis** for biological interpretation  
- Apply **deep learning models** for improved classification and feature extraction  

---

## Reproducibility

- All code, data processing steps, and figures are **fully reproducible** using `ASD_analysis.ipynb` and `requirements.txt`  
- Designed to demonstrate computational biology, programming, and ML skills relevant for **biomedical engineering research**

---

## License

This project is licensed under the **MIT License**. See `LICENSE` for details.

---

## Visual Highlights

| PCA Plot | Heatmap | Volcano Plot | Feature Importance | Confusion Matrix | 
|-----------|--------|--------------|-----------------|---------------|
| ![PCA](figures/pca_autism_samples.png) | ![Heatmap](figures/top20_genes_heatmap.png) | ![Volcano](figures/volcano_plot_autism.png) | ![Importance](figures/feature_importance_genes.png) | ![Confusion](figures/confusion_matrix.png) | 

> **Summary figure** combining all panels is displayed at the top. (except confusion matrix)

---

## Contact

**[Edith Younes]** — [younesedith@gmail.com]
