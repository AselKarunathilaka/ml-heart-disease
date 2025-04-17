# 🫀 Heart Disease Prediction using Machine Learning

This project applies supervised machine learning algorithms — K-Nearest Neighbors (KNN) and Support Vector Machine (SVM) — to predict the presence of heart disease using the UCI Cleveland Heart Disease dataset.

---

## 📌 Project Overview

- **Goal**: Predict whether a patient has heart disease based on medical attributes.
- **Dataset**: [UCI Heart Disease Dataset (Cleveland)](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
- **Algorithms Used**: 
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
- **Tools**: Python, Jupyter Notebook, scikit-learn, pandas, matplotlib, seaborn

---

## 🧪 Dataset Description

The dataset contains 13 medical features and 1 target variable:

- **Features**: age, sex, chest pain type, blood pressure, cholesterol, fasting blood sugar, ECG results, max heart rate, exercise-induced angina, ST depression, slope, number of major vessels, and thalassemia.
- **Target**: Presence of heart disease (0 = No, 1 = Yes)

After preprocessing, the target column was binarized:  
`target = 1 if disease present, else 0`

---

## ⚙️ Project Workflow

1. **Data Loading and Cleaning**  
   - Handle missing values (`?`) and convert to numeric
2. **Preprocessing**  
   - Feature scaling using `StandardScaler`
   - Train-test split (80/20)
3. **Model Training**  
   - Train KNN with k=5
   - Train SVM with a linear kernel
4. **Model Evaluation**  
   - Confusion matrix, accuracy, precision, recall, F1-score

---

## 📊 Results

| Algorithm | Accuracy |
|-----------|----------|
| KNN       | 86.67%   |
| SVM       | 90.00%   |

SVM slightly outperformed KNN, likely due to its ability to find optimal decision boundaries in high-dimensional space.

---

## 📁 Files Included

- `heart_disease_knn_svm_final.ipynb`: Jupyter Notebook containing full code
- `README.md`: This file

---

