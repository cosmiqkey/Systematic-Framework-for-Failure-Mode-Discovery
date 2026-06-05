# Failure-Aware Medical Image Classification

Code for the paper: "A Systematic Framework for Failure Mode 
Discovery and Performance Improvement in Medical Image Classification"

## Structure
notebooks/
  01_ISIC2019_failure_aware.ipynb
  02_CheXpert_failure_aware.ipynb
  03_PathMNIST_failure_aware.ipynb
  04_APTOS2019_failure_aware.ipynb
  05_BreastUSG_failure_aware.ipynb
  06_BrainMRI_failure_aware.ipynb
  07_COVID19_failure_aware.ipynb
  08_Kvasir_failure_aware.ipynb

results/
  baseline_results_{dataset}.csv
  improvement_{dataset}.csv
  cluster_profiles/

## Requirements
- Python 3.10+
- PyTorch 2.x
- timm
- umap-learn
- torchmetrics

## Running
Each notebook is self-contained and runs on Kaggle 
with a T4 GPU. Open any notebook, attach the 
corresponding dataset from Kaggle, and run all cells.
