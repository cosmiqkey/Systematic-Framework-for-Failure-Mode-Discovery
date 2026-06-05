# Failure-Aware Medical Image Classification

This repository contains the official implementation of the paper:

**“A Systematic Framework for Failure Mode Discovery and Performance Improvement in Medical Image Classification”**

---

## 📌 Overview

Deep learning models in medical imaging often achieve high accuracy but fail unpredictably on specific subsets of data. These hidden failure patterns are not captured by standard evaluation metrics.

This project introduces a **failure-aware learning framework** that systematically:

* Identifies misclassification patterns in deep models
* Extracts structured failure modes using embedding analysis
* Clusters failure samples in feature space
* Profiles error types across multiple dimensions
* Improves performance through targeted retraining

The framework is evaluated across **8 medical imaging datasets and 10 deep learning architectures**.

---

## 🧠 Key Idea

Instead of treating misclassified samples as random errors, we:

> Treat them as **structured signals of model weakness**

We analyze these errors using:

* Penultimate-layer embeddings
* PCA + UMAP dimensionality reduction
* KMeans clustering
* Confidence + calibration analysis
* Image-level feature statistics

---

## 📂 Repository Structure

```
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
```

---

## ⚙️ Requirements

* Python ≥ 3.10
* PyTorch ≥ 2.0
* timm
* umap-learn
* torchmetrics
* scikit-learn
* numpy, pandas, matplotlib

Install dependencies:

```bash
pip install torch torchvision timm umap-learn torchmetrics scikit-learn pandas matplotlib
```

---

## 🚀 Methodology Pipeline

1. Train baseline deep learning model
2. Extract misclassified samples
3. Compute penultimate-layer embeddings
4. Reduce dimensionality (PCA → UMAP)
5. Cluster failure cases using KMeans
6. Profile failure clusters:

   * Label confusion structure
   * Confidence distribution
   * Calibration (ECE)
   * Image-level statistics
7. Perform failure-aware retraining
8. Evaluate improvement in F1, Accuracy, ECE

---

## 🧪 Datasets

* ISIC 2019 (Dermoscopic skin lesions)
* CheXpert (Chest X-ray)
* PathMNIST (Histopathology)
* APTOS 2019 (Diabetic Retinopathy)
* Breast Ultrasound Images
* Brain Tumor MRI
* COVID-19 Radiography
* Kvasir (GI Endoscopy)

Total: **398,255 images across multiple modalities**

---

## 🧠 Models Used

* CNNs: ResNet-50, ResNet-101, DenseNet-121
* Efficient Models: EfficientNet-B3/B5, MobileNetV3
* Transformers: ViT-B/16, Swin-T
* Hybrids: ConvNeXt-S, MaxViT-T

---

## 📊 Results Summary

* Mean F1 improvement: **+1.7%**
* Improvement in **62/80 experiments**
* Calibration improvement in **49/80 cases**
* Best gains up to **+9.0% (dataset-dependent)**

---

## 🔥 Key Findings

* Failure patterns are **structured, not random**
* Many errors are **shared across architectures**
* Best performance gains occur in moderate difficulty datasets (65–92% accuracy range)
* Transformer models benefit most from combined retraining strategies
* Failure clusters align with **real clinical confusion patterns**

---

## 📈 Example Failure Patterns

* Melanoma ↔ Nevus (skin lesion confusion)
* Glioma ↔ Meningioma (brain MRI)
* COVID-19 ↔ Viral Pneumonia (chest X-ray)

---

## 📌 Citation

If you use this work, please cite:

```bibtex
@article{failureaware2026,
  title={A Systematic Framework for Failure Mode Discovery and Performance Improvement in Medical Image Classification},
  author={Your Name},
  year={2026}
}
```

---







