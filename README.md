# Ensemble and Hybrid Machine Learning for Psychological Prediction

This repository contains the full project for my Master's in Computer Science (MCS):
**"Ensemble and Hybrid Machine Learning Model for Interpretable Classification of Psychological Constructs Using DASS-21, SWLS, and BFI-10"**.

## 📌 Project Overview
We developed and compared multiple models for classifying:
- Depression levels (DASS-21)
- Life satisfaction (SWLS)
- Big Five personality traits (BFI-10)

## ⚙️ Methods
- Traditional ML: Logistic Regression, Decision Trees, SVM, Naive Bayes
- Ensemble ML: Random Forest, XGBoost, Stacking
- Hybrid ML: **SVM (feature extraction) + XGBoost (classification)**
- Data Augmentation: **Gaussian Noise (GNA)** and **SMOTE**
- Evaluation Metrics: Accuracy, Precision, Recall, F1, ROC-AUC
- Explainability: **SHAP** for feature importance

## 📂 Repository Structure
- `data/` → datasets (raw and processed)
- `notebooks/` → Jupyter notebooks
- `src/` → Python scripts
- `results/` → evaluation results
- `requirements.txt` → dependencies

## 📊 Results
- Hybrid SVM+XGBoost achieved **97% accuracy** for personality classification
- Stacking ensembles reached ROC-AUC of **0.98**
- SHAP analysis confirmed clinically valid feature contributions

## 🚀 Installation
```bash
git clone https://github.com/yugam0203/psychological-ml-project.git
cd psychological-ml-project
pip install -r requirements.txt
