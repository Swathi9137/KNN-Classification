# 🌸 Task 6: K-Nearest Neighbors (KNN) – Iris Dataset Classification

## 📌 Objective
Implement the **K-Nearest Neighbors (KNN)** algorithm on the Iris dataset to:
- Normalize features
- Train models using different `k` values
- Evaluate model performance
- Visualize results

## 🛠 Tools & Libraries Used
- Python
- Pandas
- Scikit-learn
- Matplotlib & Seaborn

## 📁 Dataset
**File**: `Iris.csv`  
**Target column**: `Species`  
**Feature columns**: `SepalLengthCm`, `SepalWidthCm`, `PetalLengthCm`, `PetalWidthCm`

## 🔍 Workflow Overview

1. **Data Preprocessing**:
   - Removed `Id` column
   - Standardized feature values using `StandardScaler`

2. **Model Training & Evaluation**:
   - Used `KNeighborsClassifier` from `sklearn`
   - Tried multiple values of `k`: `[1, 3, 5, 7, 9]`
   - Selected best `k` based on accuracy

3. **Metrics Used**:
   - Accuracy
   - Classification Report
   - Confusion Matrix (with heatmap)

4. **Visualization**:
   - Accuracy vs. K graph
   - Confusion matrix heatmap

## 📊 Results

| K Value | Accuracy |
|---------|----------|
| 1       | ~0.97    |
| 3       | ~0.97    |
| 5       | ~1.00    |
| 7       | ~1.00    |
| 9       | ~1.00    |

> Best performance observed for `k = 5` to `k = 9`.

## 🧠 Concepts Demonstrated

- **Instance-based learning**
- **Euclidean distance**
- Importance of **feature scaling**
- Choosing the **optimal K**
- Handling **multi-class classification** using KNN

---

## ✅ Files in the Repo

- `task6_knn_colab.ipynb`: Main notebook with code
- `Iris.csv`: Dataset file
- `README.md`: This file

