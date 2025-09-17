# UZOP-project  
# 🧠 Early-Stage Alzheimer's Disease Prediction Using Machine Learning Models

This project was developed as part of the *Introduction to Data Science* course and is based on replicating and extending the results from the scientific paper *“Early-Stage Alzheimer's Disease Prediction Using Machine Learning Models.”* The main goal was to build machine learning models to predict early stages of Alzheimer’s disease using clinical and demographic patient data.

---

## 🔍 Phase 1: Data Preparation and Visualization

In this phase, the goal was to:

- Load data from the available dataset and filter it to include **only the first visit for each patient**
- Handle missing and outlier values
- Examine basic data characteristics (row count, data types, distributions)
- Normalize values and prepare the dataset for analysis
- Visualize the data using techniques such as:
  - Correlation matrices
  - Scatter plots for each feature pair (with separate coloring for patients with and without Alzheimer’s)
  - Box plots to compare patient ages

---

## 🧪 Phase 2: Model Replication and Evaluation

- Trained the models used in the original scientific paper:
  - **Logistic Regression**
  - **Random Forest**
  - **SVM**
- Evaluated models using standard metrics:
  - Accuracy, Precision, F1-score
  - AUC/ROC curves
  - Confusion matrices
- Compared the results with those reported in the original paper

---

## 🚀 Phase 3: Improving Results

In the third phase, the goal was to improve the outcomes of the previous stages by:

- Testing new models: **XGBoost**, **LightGBM**, etc.  
- Expanding the feature set (e.g. additional processing of CDR values)  
- Optimizing hyperparameters using **GridSearchCV**  
- Further evaluating results with detailed metric comparisons and visualizations
