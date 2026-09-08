# 🛒 Smart Cart — AI-Powered Grocery Recommendation & Purchase Prediction

An end-to-end Machine Learning project that analyzes grocery transaction data to understand customer purchasing behavior, recommend relevant products, and predict whether a customer is likely to purchase a target product.

The project combines **unsupervised learning** and **supervised learning** techniques to build an intelligent grocery shopping assistant.

---

## 📌 Project Overview

Traditional grocery shopping systems mainly depend on predefined product suggestions.

This project develops an AI-powered **Smart Cart** that learns from historical customer transactions to:

- Understand customer shopping patterns
- Identify customer segments
- Recommend products based on the current shopping basket
- Predict the likelihood of purchasing a specific product
- Evaluate recommendation and classification performance

The project uses three main machine learning approaches:

1. **Bernoulli Mixture Model (BMM)**
2. **Bernoulli Naive Bayes**
3. **Logistic Regression**

For the purchase prediction task, **`whole milk`** is used as the target product.

---

# 🎯 Objectives

The main objectives of this project are:

- Analyze grocery transaction data
- Transform transaction-level data into basket-level features
- Identify frequently purchased products
- Discover customer shopping segments
- Build a probabilistic product recommendation system
- Predict whether a customer will purchase a target product
- Compare different machine learning models
- Evaluate recommendation quality using Precision@K, Recall@K and F1@K
- Evaluate classification performance using Accuracy and ROC-AUC

---

# 📊 Dataset

The project uses a grocery transaction dataset containing historical customer purchases.

### Dataset Statistics

| Attribute | Value |
|---|---:|
| Purchase Records | 38,765 |
| Customer-Date Transactions | 14,963 |
| Unique Products | 167 |
| Target Product | `whole milk` |
| Positive Transactions | 2,363 |
| Negative Transactions | 12,600 |
| Positive Class | 15.79% |
| Negative Class | 84.21% |

### Dataset Columns

```text
Member_number
Date
itemDescription
year
month
day
day_of_week
