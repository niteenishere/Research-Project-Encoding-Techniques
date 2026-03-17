# Research-Project-Encoding-Techniques
# Study of Feature Encoding Techniques for Machine Learning

## Overview

This repository contains the research project **“Study of Several Feature Encoding Methods”**, which investigates how different categorical feature encoding techniques influence the performance of supervised machine learning models.

Many real-world datasets contain **categorical variables** that cannot be directly used by machine learning algorithms. Since most machine learning models operate on numerical feature vectors, categorical variables must first be transformed into numerical representations through **feature encoding techniques**.

This project systematically studies several encoding methods and analyzes their effect on model performance, particularly when dealing with **high-cardinality categorical variables**.

---

## Research Objectives

The primary objectives of this project are:

- To understand the theoretical foundations of categorical feature encoding.
- To study different encoding techniques used in machine learning.
- To investigate the impact of encoding methods on model performance.
- To analyze how encoding methods handle **high-cardinality categorical variables**.
- To compare encoding methods using multiple supervised machine learning algorithms.

---

## Feature Encoding Techniques Studied

The following encoding techniques are studied in this project:

### Classical Encoding Methods
- Label Encoding
- One-Hot Encoding
- Contrast Encoding
- Helmert Encoding
- Backward Difference Encoding

### Dimensionality Reduction Encoders
- Binary Encoding
- Base-N Encoding

### Statistical Encoding Methods
- Frequency Encoding
- Target Encoding
- Leave-One-Out Encoding
- Weight of Evidence Encoding

### Advanced Encoding Methods
- Feature Hashing
- CatBoost Encoding
- GLMM Encoding

---

## Machine Learning Algorithms Used

To evaluate the impact of feature encoding, several supervised learning algorithms are applied:

- Logistic Regression
- Random Forest
- Gradient Boosting
- Support Vector Machine (SVM)
- k-Nearest Neighbors (KNN)

The performance of each model is evaluated after applying different encoding techniques.

---

## Datasets

Datasets used in this project are primarily obtained from **OpenML**, which provides a large collection of machine learning datasets for benchmarking and experimentation.

The selected datasets contain **categorical variables with varying cardinality**, allowing analysis of how different encoding techniques perform under different conditions.

---

## Repository Structure
