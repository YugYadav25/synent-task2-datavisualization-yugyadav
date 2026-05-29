# 🌸 Iris Flower Classification

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A professional Data Science project focused on **Iris Flower Classification** using Machine Learning. The project involves Exploratory Data Analysis (EDA), dynamic data visualizations, and classification model building using K-Nearest Neighbors (KNN).

---

## 🎯 Aim & Objectives
- Conduct **Exploratory Data Analysis (EDA)** to understand flower features (Sepal/Petal length and width).
- Create high-quality visual representations of class distributions and feature correlations.
- Train, optimize, and evaluate a **K-Nearest Neighbors (KNN)** classifier to predict Iris species (Setosa, Versicolor, Virginica).

## 📊 Dataset Used
- **Dataset:** Iris Flower Dataset
- **Source:** Automatically loaded directly from an online raw CSV source. No manual upload or local storage is required.

## 🛠️ Tech Stack & Libraries
- **Core:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `seaborn`, `matplotlib`
- **Machine Learning:** `scikit-learn` (`KNeighborsClassifier`, `train_test_split`, `accuracy_score`, `confusion_matrix`, `classification_report`)

---

## 🚀 How to Setup & Run

### 1. Clone the Repository
```bash
git clone https://github.com/yug-yadav/synent-task2-datavisualization-yugyadav.git
cd synent-task2-datavisualization-yugyadav
```

### 2. Install Dependencies
Make sure you have Python installed. Install all required packages using:
```bash
pip install -r requirements.txt
```

### 3. Launch the Jupyter Notebook
Run the following command to start Jupyter:
```bash
jupyter notebook synent_task2_datavisualization-yugyadav.ipynb
```
Run all cells in the notebook to view visualizations, model metrics, and classification reports.

---

## 📈 Methodology & Key Results
1. **EDA & Visualizations:** Utilized Seaborn pairplots and correlation heatmaps to observe clean clustering and linear separation between Iris species.
2. **Train-Test Split:** Used standard stratified splits to maintain class distributions.
3. **Model Selection & Tuning:** Implemented K-Nearest Neighbors (KNN) achieving an outstanding classification accuracy.
4. **Evaluation Metrics:** Provided detailed Confusion Matrix and Classification Report (Precision, Recall, F1-Score).

---
*Developed by Yug Yadav*
