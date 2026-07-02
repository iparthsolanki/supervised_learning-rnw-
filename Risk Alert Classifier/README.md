# Financial Risk Alert Classification using Machine Learning

A comprehensive Machine Learning project focused on predicting financial risk by classifying customers into risk categories using supervised learning algorithms. The project covers theoretical concepts, data preprocessing, handling imbalanced datasets, classification modeling, hyperparameter tuning, and model evaluation.

---

# Overview

Financial institutions process thousands of customer applications every day. Identifying high-risk customers before approving loans or financial services is critical for minimizing financial losses and improving decision-making.

This project develops a classification model that predicts whether a customer is **High Risk** or **Low Risk** based on financial and customer-related attributes.

The notebook demonstrates the complete Machine Learning pipeline, from understanding classification concepts to training and evaluating predictive models.

---

# Business Problem

Banks and financial institutions face challenges such as:

- Loan defaults
- Credit risk
- Financial fraud
- Incorrect customer classification
- High financial losses

An intelligent risk classification model helps institutions identify risky customers early and supports better lending decisions.

---

# Objectives

The main objectives of this project are:

- Understand supervised classification algorithms
- Build customer risk prediction models
- Handle imbalanced datasets
- Improve classification performance
- Compare different sampling techniques
- Optimize model performance using hyperparameter tuning

---

# Project Contents

The notebook includes:

- Classification Theory
- Logistic Regression
- Confusion Matrix
- Precision, Recall and F1-Score
- ROC-AUC Analysis
- Handling Imbalanced Data
- Under Sampling
- Over Sampling
- SMOTE
- ADASYN
- Random Forest Classification
- Hyperparameter Tuning
- Feature Importance Analysis

---

# Technologies Used

## Programming Language

- Python

## Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE, ADASYN)

---

# Machine Learning Workflow

## Step 1 — Data Collection

- Imported financial risk dataset
- Loaded customer information
- Inspected dataset structure

---

## Step 2 — Data Preprocessing

Performed:

- Missing value analysis
- Feature selection
- Train-Test Split
- Feature Scaling

---

## Step 3 — Exploratory Data Analysis (EDA)

Analyzed:

- Class distribution
- Feature relationships
- Customer risk distribution
- Data imbalance

---

## Step 4 — Logistic Regression

Implemented Logistic Regression as the baseline classification model.

Model evaluation includes:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Step 5 — Handling Imbalanced Data

Implemented multiple techniques to improve classification performance:

### Under Sampling

Reduced the majority class samples.

### Over Sampling

Increased minority class samples.

### SMOTE

Generated synthetic samples using Synthetic Minority Over-sampling Technique.

### ADASYN

Applied Adaptive Synthetic Sampling to improve minority class learning.

---

## Step 6 — Model Comparison

Compared different sampling techniques using:

- Recall
- F1 Score
- ROC-AUC Score

---

## Step 7 — Random Forest Classification

Built a Random Forest model to improve prediction accuracy.

Performed:

- Model Training
- Prediction
- Performance Evaluation

---

## Step 8 — Hyperparameter Tuning

Optimized Random Forest using:

- GridSearchCV

Parameters tuned include:

- Number of Estimators
- Maximum Depth
- Minimum Samples Split
- Splitting Criterion

---

## Step 9 — Feature Importance

Analyzed feature importance to identify the variables contributing most to customer risk prediction.

---

# Machine Learning Models Used

- Logistic Regression
- Random Forest Classifier

---

# Sampling Techniques

- Under Sampling
- Over Sampling
- SMOTE
- ADASYN

---

# Evaluation Metrics

The project evaluates models using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report

---

# Skills Demonstrated

This project demonstrates practical skills in:

- Supervised Machine Learning
- Classification
- Logistic Regression
- Random Forest
- Data Preprocessing
- Handling Imbalanced Data
- SMOTE & ADASYN
- Hyperparameter Tuning
- Feature Importance Analysis
- Model Evaluation
- Python Programming

---

# Business Applications

This project can be applied in:

- Credit Risk Analysis
- Loan Approval Systems
- Banking Analytics
- Fraud Detection
- Financial Risk Management
- Customer Risk Assessment

---

# How to Run

1. Clone the repository.
2. Install the required Python libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebook in Jupyter Notebook or Google Colab.
4. Run all cells sequentially.
5. Review model performance and classification results.

---

# Future Improvements

- XGBoost Classifier
- LightGBM
- CatBoost
- Explainable AI (SHAP)
- Streamlit Web Application
- Real-Time Risk Prediction API

---

# License

This project is created for educational and portfolio purposes.

---

# Author

**Parth Solanki**

Machine Learning Engineer | Data Scientist | Python Developer
