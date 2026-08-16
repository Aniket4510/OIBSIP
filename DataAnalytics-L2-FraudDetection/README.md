# 🚨 Fraud Detection Using Machine Learning

## 📌 Project Overview

This project focuses on detecting potentially fraudulent transactions using **Machine Learning**. The objective is to analyze transaction data, handle data imbalance, identify important features, and build a classification model capable of distinguishing between legitimate and fraudulent transactions.

This project was completed as **Project 3** during my **Data Analytics Internship at OASIS INFOBYTE**.

---

## 🎯 Objectives

* Clean and preprocess transaction data
* Perform Exploratory Data Analysis (EDA)
* Engineer relevant features
* Handle class imbalance using **SMOTE**
* Build a fraud detection classification model
* Evaluate the model using multiple performance metrics
* Identify important features contributing to fraud detection
* Understand the scalability requirements for high-volume transactions

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**

---

## 🤖 Machine Learning Model

### Random Forest Classifier

The Random Forest Classifier was used to identify fraudulent and legitimate transactions.

The model was trained after preprocessing the dataset and applying **SMOTE (Synthetic Minority Over-sampling Technique)** to address class imbalance.

---

## 🔄 Project Workflow

```text
Raw Transaction Data
        ↓
Data Cleaning & Preprocessing
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Train-Test Split
        ↓
SMOTE
        ↓
Random Forest Classifier
        ↓
Model Evaluation
        ↓
Feature Importance Analysis
        ↓
Scalability Analysis
```

---

## 📊 Model Evaluation

The model was evaluated using:

* **Precision**
* **Recall**
* **F1-Score**
* **ROC-AUC**

### Results

| Metric    |  Score |
| --------- | -----: |
| Precision | 1.0000 |
| Recall    | 0.9997 |
| F1-Score  | 0.9998 |
| ROC-AUC   | 0.9998 |

> **Note:** These results are based on the current model evaluation performed during the project.

---

## 🔍 Feature Importance

Random Forest's `feature_importances_` was used to identify the features that contributed most to the fraud classification.

This analysis helps understand which transaction attributes have the greatest influence on the model's predictions.

---

## ⚖️ Recall vs Precision

For fraud detection, **Recall is particularly important** because a false negative means an actual fraudulent transaction was not detected.

However, Precision is also important because a low Precision value can result in many legitimate transactions being incorrectly flagged as fraud.

Therefore, both metrics should be considered when evaluating a fraud detection model.

---

## 🚀 Scalability

A system processing **1 million transactions per hour** needs to handle approximately:

**278 transactions per second.**

The model's prediction throughput can be measured in transactions per second and compared with this requirement.

For higher transaction volumes, the system could use parallel processing and multiple model instances to handle predictions efficiently.

---

## 📁 Project Files

```text
DataAnalytics-L3-FraudDetection/
│
├── README.md
└── fraud_detection.ipynb
```

---

## 💡 Key Learnings

Through this project, I strengthened my practical knowledge of:

* Data preprocessing
* Exploratory Data Analysis
* Feature engineering
* Imbalanced classification
* SMOTE
* Random Forest
* Model evaluation
* Feature importance
* Fraud detection
* Machine learning scalability

---

## 🏢 Internship

**OASIS INFOBYTE**
**Data Analytics Internship**

**Project 3: Fraud Detection**

---

## 👨‍💻 Author

**Aniket Thakur**

GitHub: **Aniket4510**

---

## 🏷️ Technologies

`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Scikit-Learn` `Machine Learning` `Random Forest` `Fraud Detection` `Jupyter Notebook`

