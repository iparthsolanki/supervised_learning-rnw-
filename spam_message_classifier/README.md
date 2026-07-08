# Spam Message Classification using Machine Learning

A comprehensive Machine Learning project that classifies SMS and text messages as **Spam** or **Legitimate (Ham)** using supervised learning algorithms. The project combines probability theory, data preprocessing, feature scaling, model training, evaluation, and comparative analysis to build an intelligent spam detection system.

---

# Overview

Spam messages are one of the most common cybersecurity and communication challenges faced by businesses and individuals. Automatically detecting unwanted messages improves communication quality, enhances user experience, and protects users from phishing and fraudulent activities.

This project develops an end-to-end spam message classification system using multiple supervised machine learning algorithms. It demonstrates the complete workflow from theoretical concepts to practical implementation and model comparison.

---

# Business Problem

Organizations receive thousands of emails and SMS messages every day. Manually identifying spam messages is inefficient and prone to errors.

Challenges include:

- Spam SMS detection
- Email spam filtering
- Fraudulent message identification
- Phishing attack prevention
- Reducing unwanted advertisements
- Improving communication security

This project provides an automated machine learning solution capable of accurately classifying messages into **Spam** and **Legitimate (Ham)** categories.

---

# Objectives

The primary objectives of this project are:

- Understand probability concepts used in classification
- Explore Bayes' Theorem for spam detection
- Perform data preprocessing and feature scaling
- Train multiple classification algorithms
- Compare model performance
- Select the best-performing classifier
- Demonstrate real-world spam detection applications

---

# Dataset Information

The project uses a spam message dataset containing numerical message-related features and a target variable.

### Features Included

- Message ID
- Message Text
- Spam Keyword Score
- Message Length
- Capital Letter Count
- Digit Count
- Special Character Count
- URL Count
- Timestamp
- Other engineered numerical features

### Target Variable

- Spam Label
  - Spam
  - Legitimate (Ham)

---

# Technologies Used

## Programming Language

- Python

## Data Analysis

- Pandas
- NumPy

## Data Visualization

- Matplotlib
- Seaborn

## Machine Learning

- Scikit-learn

---

# Project Workflow

## Part A — Probability & Classification Concepts

Covered theoretical concepts including:

- Conditional Probability
- Bayes' Theorem
- Naive Bayes Assumption
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

These concepts establish the mathematical foundation for classification algorithms.

---

## Part B — Dataset Preparation

Performed:

- Dataset Loading
- Dataset Overview
- Data Type Analysis
- Missing Value Analysis
- Feature Selection
- Target Variable Identification
- Mean Imputation using SimpleImputer
- Standard Feature Scaling
- Train-Test Split (80:20)

---

## Part C — K-Nearest Neighbors (KNN)

Implemented the KNN classifier and evaluated its performance.

Analysis includes:

- Baseline Model Training
- Accuracy Evaluation
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report
- K Value Optimization
- Distance Metric Comparison
- Misclassified Message Analysis

---

## Part D — Support Vector Machine (SVM)

Implemented multiple SVM classifiers.

Models included:

- Linear Kernel
- RBF Kernel

Evaluation includes:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report
- Support Vector Analysis

---

## Part E — Naive Bayes Classifier

Implemented Gaussian Naive Bayes for probabilistic spam classification.

Performed:

- Model Training
- Model Evaluation
- Confusion Matrix
- Classification Report
- Manual Conditional Probability Calculation
- Bayes' Theorem Demonstration
- Posterior Probability Analysis
- Probability Prediction Comparison

---

## Part F — Model Comparison

Compared all classifiers using:

- Accuracy
- Precision
- Recall
- F1 Score

Created:

- Performance Comparison Table
- Accuracy Comparison Chart
- Precision Comparison Chart
- Recall Comparison Chart
- F1 Score Comparison Chart
- Overall Performance Visualization

Selected the best-performing classifier based on overall evaluation metrics.

---

## Part G — Final Analysis

Included:

- Project Summary
- Business Interpretation
- Best Model Selection
- Real-World Applications
- Future Scope
- Final Conclusion

---

# Machine Learning Algorithms Used

- K-Nearest Neighbors (KNN)
- Support Vector Machine (Linear Kernel)
- Support Vector Machine (RBF Kernel)
- Gaussian Naive Bayes

---

# Data Preprocessing Techniques

The project includes:

- Missing Value Imputation
- Mean Imputation
- Feature Selection
- Feature Scaling
- StandardScaler
- Train-Test Split

---

# Model Evaluation Metrics

The performance of each classifier is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

# Probability Concepts Covered

The notebook explains:

- Conditional Probability
- Bayes' Theorem
- Posterior Probability
- Prior Probability
- Likelihood
- Naive Bayes Assumption

---

# Visualizations

The project includes multiple visualizations such as:

- Confusion Matrix Heatmaps
- Accuracy Comparison
- Precision Comparison
- Recall Comparison
- F1 Score Comparison
- Overall Model Performance Charts

---

# Skills Demonstrated

This project demonstrates practical experience in:

- Machine Learning
- Classification Algorithms
- Probability Theory
- Bayes' Theorem
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Naive Bayes
- Feature Scaling
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Model Evaluation
- Comparative Performance Analysis
- Python Programming

---

# Business Applications

This project can be applied in:

- Email Spam Filtering
- SMS Spam Detection
- Phishing Detection
- Fraud Message Detection
- Customer Communication Systems
- Social Media Content Moderation
- Cybersecurity Applications

---

# Project Structure

```
Spam-Message-Classification/
│
├── Message_Intelligence.ipynb
├── Message_Intelligence_Dataset.csv
├── requirements.txt
├── README.md
└── Images/
```

---

# How to Run

1. Clone the repository.

```bash
git clone https://github.com/yourusername/Spam-Message-Classification.git
```

2. Install required libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebook in Jupyter Notebook or Google Colab.

4. Run all cells sequentially.

5. Compare the performance of KNN, SVM, and Naive Bayes classifiers.

---

# Key Outcomes

- Successfully classified spam and legitimate messages.
- Demonstrated the impact of feature scaling on distance-based algorithms.
- Compared multiple supervised learning algorithms.
- Selected the best-performing model based on evaluation metrics.
- Applied probability concepts to practical machine learning classification.

---

# Future Improvements

- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Word Embeddings
- Deep Learning (LSTM, GRU)
- Transformer Models (BERT)
- Streamlit Web Application
- Real-Time Spam Detection API

---

# License

This project is created for educational and portfolio purposes.

---

# Author

**Parth Solanki**

Data Analyst | Machine Learning Engineer | Python Developer
