# ML Cardiovascular Diseases Prediction Comparison

## Overview

This project presents a comparative analysis of machine learning models for predicting cardiovascular diseases, including **heart disease** and **stroke**, using real-world healthcare data from the BRFSS 2022 dataset.

The study focuses on handling **imbalanced data** and improving model performance for clinical screening tasks where **recall is critical**.

---

## Objectives

* Compare performance of multiple ML models
* Handle class imbalance using SMOTE
* Optimize classification thresholds
* Evaluate models using clinically relevant metrics

---

## Models Used

* Logistic Regression
* Decision Tree
* Random Forest
* LightGBM
* XGBoost

---

## Techniques & Methods

* Data preprocessing (cleaning, encoding, scaling)
* Missing data imputation (KNN, mode)
* Outlier removal (IQR)
* SMOTE (Synthetic Minority Oversampling)
* Threshold tuning (F1-score optimization)
* Stratified train-test split

---

## Evaluation Metrics

* Accuracy
* Precision
* Recall (key metric)
* F1-score
* ROC AUC
* Confusion Matrix

---

## Key Results

* **XGBoost** achieved the best overall performance
* **LightGBM** provided strong balance between recall and precision
* **Logistic Regression & Decision Tree** showed high recall but low precision
* **Random Forest** performed poorly on imbalanced data

---

## Dataset

* Source: BRFSS 2022 (CDC)
* Two tasks:

  * Heart Disease Prediction (~12% positive)
  * Stroke Prediction (~4.5% positive)

---
