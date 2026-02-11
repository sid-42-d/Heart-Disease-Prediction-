# Heart Disease Risk Classification using Gaussian Naive Bayes

## Overview

This project was conducted as part of independent exploration into machine learning applications in cardiovascular risk prediction.

The project implements a probabilistic machine learning model for **heart disease risk classification** using structured clinical data. The objective is to evaluate the effectiveness of Gaussian Naive Bayes in predicting cardiovascular disease based on patient health parameters.

The study emphasizes structured feature-based classification and statistical modeling assumptions in clinical datasets.

---

## Dataset

- Total samples: **303 clinical patient records**
- Features: 13 structured clinical attributes
- Target variable: Binary output  
  - 0 = No Heart Disease  
  - 1 = Presence of Heart Disease  

### Key Clinical Features:
- Age  
- Sex  
- Chest pain type (cp)  
- Resting blood pressure (trtbps)  
- Cholesterol (chol)  
- Maximum heart rate achieved (thalachh)  
- Exercise-induced angina (exng)  
- ST depression (oldpeak)  
- Number of major vessels (caa)  
- Thalassemia type (thall)  

Duplicate records were identified and removed prior to modeling.

---

## Methodology

### 1. Data Preprocessing
- Removed duplicate entries
- Performed exploratory data analysis (EDA)
- Visualized feature distributions and class-wise comparisons
- Applied **StandardScaler** for feature normalization
- Split dataset into training and testing sets (75% / 25%)

### 2. Model Implementation

Implemented a **Gaussian Naive Bayes (GNB)** classifier:

- Assumes conditional independence between features
- Suitable for continuous features under Gaussian distribution assumption
- Computationally efficient probabilistic classifier

---

## Problem Statement

To develop a classification model capable of predicting the presence of heart disease using structured clinical features, enabling early-stage cardiovascular risk assessment through probabilistic modeling.

---

## Results

- **Test Accuracy:** 86.84%
- Evaluation Metrics:
  - Confusion Matrix
  - ROC–AUC
  - Classification Accuracy

The model demonstrates strong predictive capability despite the independence assumption inherent in Naive Bayes.

---

## Technical Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Key Learnings

- Importance of feature normalization in probabilistic models
- Understanding independence assumptions in Naive Bayes
- Model evaluation techniques for clinical binary classification
- Trade-offs between model simplicity and predictive performance

---

## Future Improvements

- Comparative analysis with Logistic Regression and SVM
- Cross-validation for robustness assessment
- Feature selection and dimensionality reduction
- Model calibration for improved clinical interpretability

---

## Author

**Siddhant Pastapure**  
B.Tech, Biomedical Engineering  
National Institute of Technology, Raipur
