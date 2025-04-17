# 🫀 Heart Disease Prediction using KNN & SVM

This project predicts the likelihood of heart disease using two supervised learning algorithms: **K-Nearest Neighbors (KNN)** and **Support Vector Machine (SVM)**. It uses real clinical data from the UCI Cleveland Heart Disease dataset.

---

## 📊 Objective

Early prediction of heart disease can help in timely treatment. This model classifies patients as having or not having heart disease based on various health attributes.

---

## 📚 Dataset

- Source: [UCI Cleveland Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
- 13 features like age, blood pressure, cholesterol, etc.
- Original target values (0–4) converted to binary (0 = no disease, 1 = disease).
- Cleaned and standardized using `StandardScaler`.

---

## 🔍 Models Used

- **KNN (k=5)**: Classifies a patient based on the majority class of its nearest neighbors.
- **SVM (linear kernel)**: Finds the optimal hyperplane to separate the classes.

---

## ⚙️ Process Overview

1. Load and clean dataset.
2. Handle missing values and convert types.
3. Scale features and split into train/test sets.
4. Train and evaluate both models.
5. Compare accuracy and performance metrics.

---

## 📈 Results

| Model | Accuracy |
|-------|----------|
| KNN   | 86.67%   |
| SVM   | 90.00%   |

SVM performed slightly better than KNN, likely due to its effectiveness with linearly separable data.

---

## 📁 Included Files

- `heart_disease_knn_svm_final.ipynb`: Main notebook with code.
- `README.md`: This file.

---


