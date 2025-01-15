# AI-Driven Insights: Machine Learning Models for Chronic Kidney Disease (CKD) Prediction

## Overview

Chronic Kidney Disease (CKD) is a major global health concern, impacting millions of people worldwide. detection is critical for improving patient outcomes, yet it remains challenging due to the silent progression of the disease. This project leverages **Machine Learning (ML)** techniques, enhanced by **Explainable AI (XAI)**, to accurately predict CKD and provide interpretable insights into the contributing factors.

The goal of this project is to not only build high-performing models but also to ensure transparency and trust by explaining model predictions to healthcare professionals.

---

## Features

- **Data Preprocessing:**
  - Cleaning, imputation, and balancing the dataset.
  - Outlier handling using medically accepted ranges.
  - Creation of three datasets:
    1. Original Cleaned Dataset
    2. Imputed Dataset
    3. SMOTE-Balanced Dataset

- **Model Development:**
  - Implemented and optimized **Random Forest**, **Decision Tree**, **KNN**, and **Artificial Neural Network (ANN)** models.
  - Hyperparameter tuning for optimal model performance.

- **Explainability:**
  - Integrated **LIME** (Local Interpretable Model-agnostic Explanations) to explain individual predictions.
  - Confidence scores included for each prediction.

- **Prediction Functionality:**
  - Allows real-time prediction using patient data.
  - Generates visual explanations for predictions using LIME.

---

## Dataset

The dataset used in this project is sourced from the [UCI Machine Learning Repository: Chronic Kidney Disease Dataset](https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease). It contains 400 records with 24 features, including both numerical and categorical attributes.

### Data Features

- **Numerical Features:** Age, Blood Pressure, Specific Gravity, Hemoglobin, Blood Glucose Random, Serum Creatinine, etc.
- **Categorical Features:** Red Blood Cells, Pus Cells, Diabetes Mellitus, Hypertension, Appetite, etc.

---

## Requirements

### Libraries and Tools

- **Python**: 3.7+
- **Google Colab** or Local Environment
- Required Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `sklearn`
  - `lime`
  - `tensorflow`
  - `imblearn`

Key Results
Model Performance Comparison
Model	Accuracy	Precision	Recall	F1-Score
Random Forest	98.75%	98%	99%	99%
Artificial Neural Network (ANN)	98.75%	99%	99%	99%
Decision Tree	97.50%	98%	97%	97%
K-Nearest Neighbors	97.50%	98%	97%	97%
Explainability with LIME
Random Forest and ANN predictions were explained using LIME to provide insights into the top contributing features for each prediction.

