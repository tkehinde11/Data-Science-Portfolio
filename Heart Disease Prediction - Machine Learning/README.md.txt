# Heart Disease Prediction

## Overview
This project applies machine learning to predict the likelihood of heart disease based on patient health data. By benchmarking multiple classifiers and comparing their performance, the analysis provides insights into which models are most effective for early detection, where recall (catching as many true cases as possible) is prioritised over overall accuracy.

## Features
- **Data Import & Preparation**: Load patient health dataset, define features and labels, and split into training/testing sets.
- **Model Training**:
  - **Scale-Insensitive Models**: Random Forest, Gaussian Naive Bayes, Gradient Boosting.
  - **Scale-Sensitive Models**: K-Nearest Neighbours (KNN), Logistic Regression, Support Vector Classifier (SVC) with feature scaling.
- **Evaluation Metrics**:
  - Accuracy and recall scores.
  - ROC/AUC comparison for model performance.
- **Trade-Offs**:
  - Compare interpretability vs predictive power across models.
  - Explore how scaling impacts algorithm effectiveness.

## Tools Used
- **Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)**: Data analysis, preprocessing, model building, and evaluation.
- **Jupyter Notebook**: Interactive environment for experiments and analysis.
- **CSV**: Dataset format.

## Key Insights
- Scale-insensitive models like Random Forest and Gradient Boosting perform strongly without preprocessing.
- Scaling features improves the performance of KNN, Logistic Regression, and SVM.
- In medical contexts, recall is prioritised to minimise false negatives, highlighting trade-offs in model selection.
- Ensemble methods provide a balance between interpretability and predictive power.
