Handling class imbalance in Heart Disease Prediction using SMOTE and SMOTE-ENN
Overview
This project addresses the class imbalance problem in heart disease prediction using the Kaggle Heart Disease dataset. The work involves applying oversampling (SMOTE) and hybrid resampling (SMOTE-ENN) techniques to improve the performance of various machine learning models.

Dataset
Source: Kaggle Heart Disease Dataset https://www.kaggle.com/datasets/mfarhaannazirkhan/heart-dataset/data
Includes raw data and a cleaned, merged file.
Contains features related to patient demographics, clinical measurements, and diagnostic attributes.

Methodology
Data Preprocessing: Cleaning, handling missing values, normalization.
Feature Engineering: Feature selection and transformation to enhance model performance.
Resampling Techniques: SMOTE (Synthetic Minority Over-sampling Technique): Balances class distribution by generating synthetic samples.
SMOTE-ENN (SMOTE + Edited Nearest Neighbors): Combines oversampling with noise reduction for better data quality.

Model Training: Eight machine learning classifiers are applied for heart disease prediction.
Classifiers Used
Logistic Regression(LR)
K-Nearest Neighbors (KNN)
Decision Tree (DT)
Random Forest (RF)
Support Vector Machine (SVM)
Gradient Boosting (GB)
AdaBoost (ABC)
Naïve Bayes (NB)

Evaluation Metrics
Accuracy
Precision, Recall, F1-score
ROC-AUC

How to Use
Open the Colab file.
Upload the dataset or load it directly from Kaggle.
Run each cell in sequence.
Compare model results with and without resampling.
