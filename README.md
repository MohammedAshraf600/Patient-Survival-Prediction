# 🧬 Patient Survival Prediction

## 📌 Project Overview
This project focuses on building a **machine learning model to predict patient survival** based on clinical and demographic data. The notebook implements a complete data science workflow including **data loading, preprocessing, exploratory data analysis (EDA), model building, evaluation, and interpretation**.

The aim is to help healthcare professionals identify high-risk patients and support decision-making using predictive analytics.

---

## 🧠 Objectives
- Load and explore the patient survival dataset
- Clean and preprocess the data
- Perform exploratory data analysis
- Train and evaluate one or more machine learning models
- Interpret model performance
- Visualize results

---

## 📂 Dataset
The dataset used in this project contains patient medical records with features such as patient demographics, clinical measurements, and survival outcomes.

The **target variable** is whether a patient survived within a specified time frame (binary: `0` for non-survival, `1` for survival).

> *Note:* Place the dataset file (e.g., `patient_survival_data.csv`) in the same directory before running the notebook.

---

## 🧹 Data Preprocessing
- Handling missing values
- Encoding categorical features
- Feature scaling (if necessary)
- Train/test split for modeling
- Visualization of distributions and correlations

---

## 📊 Exploratory Data Analysis (EDA)
The notebook includes:
- Visualization of feature distributions
- Correlation heatmaps
- Survival count plots
- Feature relationships with the outcome

These EDA steps help in understanding patterns and relationships in the data before modeling.

---

## 🤖 Machine Learning Models
This project demonstrates one or more predictive models:

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine
- Gradient Boosting
- XGBoost (optional)

Evaluation metrics include:
- Accuracy
- Confusion Matrix
- Classification Report
- ROC Curve & AUC (if applicable)

---

## 📈 Evaluation Metrics
Common evaluation metrics used in this project:
- **Accuracy** – proportion of correctly classified patients
- **Precision / Recall / F1-Score** – detailed performance per class
- **ROC AUC** – trade-off between true positive and false positive rates

---

## 📌 Results Summary
After running multiple models, the notebook compares their performance and highlights the most effective approach for predicting survival. Feature importance and model interpretability visualizations are also included.

---

## 🛠 Tools & Libraries
The following Python libraries are used throughout the project:

- `pandas`, `numpy` – Data manipulation
- `matplotlib`, `seaborn` – Visualization
- `scikit-learn` – Machine learning models and evaluation
-  `xgboost` – Gradient boosting model

