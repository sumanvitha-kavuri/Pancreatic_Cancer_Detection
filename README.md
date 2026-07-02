# 🧬 Early Pancreatic Cancer Detection Using a Hybrid Stacking Ensemble Model (IEEE explore Publication)

**Paper Link:** https://ieeexplore.ieee.org/document/11308397

## Overview

This project presents a machine learning framework for the early detection of pancreatic cancer using a hybrid stacking ensemble model. By integrating multiple machine learning algorithms with a comprehensive data preprocessing pipeline, the proposed approach aims to improve diagnostic accuracy and support timely clinical decision-making.

The research has been published in **IEEE** and is **Scopus-indexed**, demonstrating its academic and practical significance.

---

## Publication

* **Title:** *Early Pancreatic Cancer Detection Using a Hybrid Stacking Ensemble Model*
* **Publisher:** IEEE
* **Indexing:** Scopus

---

## Key Features

* Hybrid stacking ensemble architecture
* Comprehensive data preprocessing pipeline
* Missing value imputation
* Feature scaling and normalization
* Class imbalance handling using SMOTE
* Hyperparameter optimization
* Cross-validation for robust model assessment
* SHAP-based model interpretability
* Performance evaluation using multiple classification metrics

---

## Machine Learning Models

The proposed stacking ensemble combines the strengths of multiple algorithms:

* XGBoost Classifier (Base Learner)
* Multi-Layer Perceptron (MLP) (Base Learner)
* Logistic Regression (Meta Learner)
* Random Forest (Baseline Model)

---

## Dataset

This study utilizes the **Debernardi et al. (2020) Pancreatic Cancer Dataset**, which contains patient demographics and biomarker information for pancreatic cancer diagnosis.


---

## Data Preprocessing

To ensure high-quality model performance, the following preprocessing techniques were applied:

* Missing value imputation
* Outlier detection and handling
* Feature scaling using **StandardScaler**
* One-hot encoding for categorical variables
* **SMOTE** (Synthetic Minority Over-sampling Technique) for class balancing

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* SHAP
* Matplotlib
* Seaborn
* Feature-engine
* Imbalanced-learn (SMOTE)
* Jupyter Notebook

---

## Model Evaluation

The model was evaluated using multiple performance metrics to ensure reliability and generalization:

* Accuracy
* Cross-validation Accuracy
* ROC-AUC Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## Results

The proposed hybrid stacking ensemble demonstrated superior performance compared to the individual machine learning models.

| Metric                    |      Score |
| ------------------------- | ---------: |
| Test Accuracy             | **98.21%** |
| Cross-validation Accuracy | **92.24%** |

The results indicate that combining multiple classifiers through stacking significantly improves predictive performance while maintaining strong generalization capability.

---

## Repository Structure

```text
├── Pancreatic_cancer.ipynb
├── README.md
└── Debernardi et al 2020 data.csv
```



