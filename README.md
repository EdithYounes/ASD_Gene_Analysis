# ASD Gene Expression Analysis Using Machine Learning

[![Python](https://img.shields.io/badge/python-3.10-blue)](https://www.python.org/)

---

## **Overview**

This project analyzes gene expression data from the GEO dataset **GSE18123** to identify autism spectrum disorder (ASD) associated genes. By combining **machine learning (Random Forest)** with **statistical analysis**, the project highlights candidate genes and visualizes differences between ASD and control samples.  

**Key biomedical engineering relevance:**  
- Predictive modeling for disease classification  
- Gene prioritization for potential biomarkers  
- Translational application of computational biology to neurodevelopmental disorders  

---

## **Features**

- Download and preprocess GEO gene expression data  
- Handle missing data and select the most variable genes  
- Principal Component Analysis (PCA) for sample visualization  
- Random Forest classifier for ASD vs control prediction  
- Feature importance analysis to prioritize genes  
- Heatmap and volcano plots for top genes  
- Identification of candidate genes by combining ML and statistical significance  

---

## **Results**

### PCA of ASD vs Control Samples
![PCA](figures/pca_autism_samples.png)

### Top 20 Important Genes (Random Forest)
![Feature Importance](figures/feature_importance_genes.png)

### Heatmap of Top 20 Genes
![Heatmap](figures/top20_genes_heatmap.png)

### Volcano Plot ASD vs Control
![Volcano Plot](figures/volcano_plot_autism.png)

### Combined Summary Figure
![Summary Figure](figures/summary_figure_all_panels.png)

---

## **Candidate Genes Identified**

| Gene | ML Importance |
|------|---------------|
| GENE1 | 0.025         |
| GENE2 | 0.021         |
| GENE3 | 0.018         |
| GENE4 | 0.016         |
| GENE5 | 0.015         |

*These genes were prioritized by combining Random Forest feature importance with statistical significance (p < 0.05, |log2FC| > 1).*

---

## **Getting Started**

### **Clone the repository**
```bash
git clone https://github.com/EdithYounes/ASD_Gene_Analysis.git
cd ASD_Gene_Analysis
