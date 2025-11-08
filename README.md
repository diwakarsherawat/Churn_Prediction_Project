# **Customer Churn Prediction Project**

This project presents a machine learning-based framework for predicting customer churn in the telecommunications industry. The primary goal is to identify customers at high risk of leaving and analyze the key factors driving this decision.

**Authors:**

- Rony Biju

- Shruti Gupta

- Diwakar Sherawat

- Sneha Narwal

- Abhay Manhas

- Under the guidance of Dr. Monica Luthra


## **Project Overview**

Customer churn is a significant challenge in the telecom industry. This project tackles the problem by applying machine learning models to the IBM Telco Customer Churn dataset.

The workflow involved data preprocessing, exploratory data analysis (EDA), handling class imbalance with SMOTE, and K-Means clustering for customer segmentation. We then trained and evaluated four models to predict churn: Logistic Regression, Random Forest, XGBoost, and an Artificial Neural Network (ANN).


## **Key Findings**

The models were evaluated on Accuracy, Precision, Recall, F1-score, and ROC-AUC. The ensemble models performed best, with **XGBoost** emerging as the top-performing model, demonstrating a robust ability to predict churn accurately.


### **Model Performance Comparison**

|                     |              |               |            |              |             |
| ------------------- | ------------ | ------------- | ---------- | ------------ | ----------- |
| **Model**           | **Accuracy** | **Precision** | **Recall** | **F1-score** | **ROC-AUC** |
| Logistic Regression | 0.81         | 0.74          | 0.69       | 0.71         | 0.82        |
| Random Forest       | 0.86         | 0.80          | 0.77       | 0.78         | 0.87        |
| **XGBoost**         | **0.88**     | **0.83**      | **0.81**   | **0.82**     | **0.89**    |
| Neural Network      | 0.87         | 0.82          | 0.78       | 0.80         | 0.88        |


## **Repository Contents**

This repository contains the documentation for the research project:

- Customer Churn Prediction Project.docx: The full research paper detailing the project's background, methodology, results, and conclusion.

- Customer Churn Prediction.pptx: A slide-deck presentation summarizing the project.

- README.md: This file.
