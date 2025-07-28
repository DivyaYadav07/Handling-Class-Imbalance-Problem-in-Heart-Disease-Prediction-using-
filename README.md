# Handling Class Imbalance in Heart Disease Prediction using SMOTE and SMOTE-ENN

## Overview
This project addresses the **class imbalance problem** in heart disease prediction using the Kaggle Heart Disease dataset. The work involves applying **oversampling (SMOTE)** and **hybrid resampling (SMOTE-ENN)** techniques to improve the performance of various machine learning models.

## Dataset
**Source:** [Kaggle Heart Disease Dataset](https://www.kaggle.com/datasets/mfarhaannazirkhan/heart-dataset/data)  
Includes raw data and a cleaned, merged file. Contains features related to patient demographics, clinical measurements, and diagnostic attributes.

## Methodology
- **Data Preprocessing:** Cleaning, handling missing values, normalization  
- **Feature Engineering:** Feature selection and transformation  
- **Resampling Techniques:**  
  - **SMOTE:** Balances class distribution by generating synthetic samples  
  - **SMOTE-ENN:** Combines oversampling with noise reduction  

## Model Training
Eight machine learning classifiers are applied:  
Logistic Regression, KNN, Decision Tree, Random Forest, SVM, Gradient Boosting, AdaBoost, Naïve Bayes

## Evaluation Metrics
- Accuracy  
- Precision, Recall, F1-score  
- ROC-AUC  

## How to Use
1. Open the Colab file  
2. Upload the dataset or load it from Kaggle  
3. Run each cell sequentially  
4. Compare model results with and without resampling

