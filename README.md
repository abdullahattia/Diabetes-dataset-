# Diabetes-dataset-

📌 Project Overview

This project aims to compare the performance of several supervised learning algorithms on a binary classification problem. It includes:

Data preprocessing and splitting into train, validation, and test sets.

Model training with GridSearchCV for hyperparameter tuning.

Evaluation using accuracy, precision, recall, F1-score, and confusion matrices.

Visualization of cross-validation scores for model comparison.

Additional experiment: Training XGBoost on unscaled data to measure scaling effects.

🛠 Models Used

Support Vector Machine (SVM)

Decision Tree

Random Forest

XGBoost (scaled & unscaled)

K-Nearest Neighbors (KNN)

Logistic Regression

📊 Results Summary

Best Cross-Validation Performance: Logistic Regression (0.7765)

Most Consistent Performance: Random Forest & XGBoost (~0.75 accuracy)

Best Test Accuracy: Decision Tree (0.7672)

Class 0 had higher recall across all models; Class 1 was harder to predict.

📂 Files Included

dataset.csv – The dataset used for training/testing.

classification_models.ipynb – Jupyter Notebook with full code, results, and visualizations.

🚀 How to Run

Download the dataset and notebook.

Install dependencies:

pip install pandas numpy matplotlib scikit-learn xgboost


Open the notebook:

jupyter notebook classification_models.ipynb


Run all cells to reproduce results.

📈 Visualizations

Model CV accuracy comparison bar chart.

Confusion matrices for each model.
