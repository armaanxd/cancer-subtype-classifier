# Cancer Subtype Classifier — TCGA BRCA

> Classifying breast cancer molecular subtypes (Luminal A, Luminal B, 
> HER2-enriched, Basal-like) from RNA-seq gene expression data.

## Status
🔨 In progress

## Approach
- Dataset: TCGA-BRCA (~1,100 samples, 20,531 genes)
- Dimensionality reduction: PCA + UMAP
- Models: Random Forest, SVM, Logistic Regression
- Evaluation: 5-fold stratified cross-validation

## Results
*(Will be updated as experiments complete)*

## Setup
```bash
pip install -r requirements.txt
jupyter notebook notebooks/01_eda.ipynb
```

