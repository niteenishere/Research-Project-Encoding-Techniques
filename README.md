# 📊 Study of Feature Encoding Techniques in Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)
![Status](https://img.shields.io/badge/Project-Research-orange)
![License](https://img.shields.io/badge/License-Academic-lightgrey)

## 📌 Overview

This repository contains the research project **“Study of Feature Encoding Techniques”**, which investigates how different categorical feature encoding techniques influence the performance of supervised machine learning models.

Many real-world datasets contain **categorical variables** that cannot be directly used by machine learning algorithms. Since most ML algorithms operate on **numerical feature vectors**, categorical variables must first be transformed into numerical representations using **feature encoding techniques**.

This project studies several encoding approaches and evaluates how they affect model performance, particularly in datasets containing **high-cardinality categorical variables**.

---

## 🎯 Research Objectives

The main goals of this research are:

- To understand the theoretical foundations of categorical feature encoding.
- To study multiple encoding techniques used in machine learning.
- To evaluate the impact of encoding techniques on model performance.
- To investigate how encoding techniques handle **high-cardinality categorical variables**.
- To compare encoding techniques across multiple supervised ML algorithms.

---

## 🧠 Encoding Techniques Studied

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

### Advanced Encoding Techniques
- Feature Hashing
- CatBoost Encoding
- GLMM Encoding

---

## 🤖 Machine Learning Algorithms Used

To evaluate encoding techniques, the following supervised models are applied:

- Logistic Regression
- Random Forest
- Gradient Boosting
- Support Vector Machine (SVM)
- k-Nearest Neighbors (KNN)

Each encoding technique is applied before model training, and model performance is compared.

---

## 🗂️ Datasets

Datasets used in this project are primarily obtained from **OpenML**.

These datasets contain categorical variables with varying levels of cardinality, allowing systematic comparison of encoding methods.

Example datasets include:

- Adult Census Dataset
- Bank Marketing Dataset
- Nomao Dataset
- Internet Advertisement Dataset
- Connect-4 Dataset

---

## ⚙️ Experimental Workflow

The workflow followed in this research project is shown below:

---

## 📁 Repository Structure

---

## 🛠️ Installation

Clone the repository:

Install required libraries:

---

## 🚀 How to Run Experiments

1. Load dataset
2. Identify categorical variables
3. Apply encoding techniques
4. Train machine learning models
5. Evaluate and compare model performance

Example:

---

## 📊 Research Questions

This project aims to answer the following questions:

- How do different encoding techniques affect ML model performance?
- Which encoding methods perform best for **high-cardinality categorical variables**?
- Do advanced encoding techniques outperform classical encoding methods?
- How does the choice of encoding influence model stability?

---

## 📚 References

Key research papers used in this project include:

- Micci-Barreca (2001) – Target Encoding
- Weinberger et al. (2009) – Feature Hashing
- Guo & Berkhahn (2016) – Entity Embeddings
- Hancock & Khoshgoftaar (2020) – Survey on Categorical Data
- Pargent et al. (2021) – Regularized Target Encoding

---

## 👨‍🎓 Author

**Ricky**  
M.Sc. Statistics  
North Maharashtra University, Jalgaon

---

## 📄 License

This repository is intended for **academic and research purposes**.
