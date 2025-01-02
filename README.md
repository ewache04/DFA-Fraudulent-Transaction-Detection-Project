
# Credit Card Fraud Detection Using Machine Learning

## Abstract
Credit card fraud is a significant global issue, with billions of dollars lost annually. Machine learning can effectively detect fraud by identifying patterns indicative of unauthorized transactions. Fraudulent activities include the physical theft of credit cards or the compromise of sensitive credit card information. This project aims to develop machine learning models to detect fraudulent transactions. The models are trained on historical transaction data and evaluated on holdout datasets to ensure accuracy and generalization.

**Keywords:** Credit Card Fraud Detection, Fraud Detection, Fraudulent Transactions, K-Nearest Neighbors, Support Vector Machine, Logistic Regression, Decision Tree.

---

## Overview
As the use of credit cards continues to rise globally, credit card companies must prioritize customer security. In 2019, 2.8 billion people used credit cards worldwide, with 70% owning at least one card. Reports of credit card fraud in the U.S. increased by **44.7%** between 2019 and 2020. Fraud typically occurs in two forms:
1. Identity theft, where a new account is created in the victim's name.
2. Unauthorized use of an existing account by stealing card information.

The rapid increase in such incidents motivated this project, which applies machine learning techniques to analyze credit card transactions and identify fraudulent behavior.

---

## Project Goals
The primary goal of this project is to detect fraudulent credit card transactions, ensuring customers are not charged for purchases they did not make. This is achieved by:
1. Applying multiple machine learning algorithms to a labeled dataset.
2. Comparing model outcomes to determine the most accurate and efficient approach.
3. Analyzing previous literature to explore techniques used for fraud detection.

The results aim to enhance fraud detection systems and improve customer confidence in credit card security.

---

## Data Source
The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). It contains:
- **284,807 transactions**, including 492 fraudulent cases.
- **31 attributes**, with 28 anonymized numerical features transformed using PCA for privacy.
- Attributes include:
  - `Time`: Elapsed time between transactions.
  - `Amount`: Transaction value.
  - `Class`: Binary label indicating fraud (`1` for fraudulent, `0` for non-fraudulent).

This dataset provides a comprehensive basis for training and evaluating machine learning models.

---

## Algorithms
Four machine learning algorithms were implemented to detect fraudulent transactions:
1. **K-Nearest Neighbors (KNN):** A distance-based algorithm that classifies transactions by comparing them with the closest neighbors.
2. **Logistic Regression (LR):** A probabilistic model that predicts fraud based on a logistic curve.
3. **Support Vector Machine (SVM):** A classification model that maximizes the margin between fraudulent and non-fraudulent classes.
4. **Decision Tree (DT):** A rule-based model that splits data into branches to classify transactions.

---

## Future Work
To further improve the system, future enhancements could include:
1. Testing the models on datasets of varying sizes and characteristics.
2. Altering data-splitting ratios to evaluate model performance under different training and testing conditions.
3. Integrating additional data types, such as geolocation, to detect anomalies. For example, if a card owner is in Dubai but their card is used in Abu Dhabi, it can be flagged as suspicious.
4. Exploring ensemble techniques that combine multiple algorithms for better accuracy.

---

## Conclusion
This project successfully implemented machine learning models to detect credit card fraud. Among the algorithms tested, **K-Nearest Neighbors (KNN)** and **Decision Tree (DT)** achieved perfect accuracy, making them the most effective models for this dataset. These results demonstrate the potential of machine learning to improve fraud detection, enhance customer satisfaction, and ensure a secure transaction experience.

---