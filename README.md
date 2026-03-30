# customer-segmentation-classification
# 👥 Customer Segmentation Classification Model

## 📌 Project Overview
This project analyzes a labeled customer segmentation dataset from Kaggle for an automobile company. Customers are categorized into **four segments (A, B, C, and D)** based on demographic and behavioral characteristics.

The objective is to understand customer profiles and develop models capable of accurately classifying new customers into the appropriate segment, enabling **targeted marketing, personalization, and data-driven business decisions**.

---

## 📊 Dataset Description

- Source: Kaggle Customer Segmentation Dataset
- Problem Type: Multiclass Classification
- Target Variable: `Segmentation` (A, B, C, D)

### Features Included
- Age
- Gender
- Marital Status
- Education Level
- Profession
- Work Experience
- Spending Score
- Family Size
- Anonymized categorical variable
- Customer ID (removed during preprocessing)

---

## 🔎 Project Workflow

### 1️⃣ Data Preprocessing
- Merged training and test datasets
- Removed duplicate records
- Converted text variables to categorical types
- Missing value imputation:
  - Mode (categorical variables)
  - Median (numerical variables)
- Stratified train–test split
- Removed non-informative ID variables

---

### 2️⃣ Exploratory Data Analysis (EDA)
Descriptive analysis was conducted to understand customer behavior and segment characteristics:

- Distribution of customer segments
- Relationship between segments and:
  - Spending score
  - Gender
  - Marital status
  - Education level
  - Profession
  - Family size
  - Work experience
  - Age distribution

---

### 3️⃣ Modeling Approach (Planned & Evaluated)
The project explores classification and segmentation strategies including:

#### Supervised Learning
- Random Forest (proposed)
- XGBoost (proposed)

#### Dimensionality Reduction
- Principal Component Analysis (PCA)

#### Unsupervised Learning (Exploration)
- K-Means Clustering for deeper customer structure analysis

---

## 📈 Model Evaluation Strategy
Performance evaluation methods include:

- Confusion Matrix
- Classification Accuracy
- ROC Curves
- Segment-wise performance comparison

---

## ⭐ Key Insights
- Customer segments differ significantly in spending behavior and demographic attributes.
- Spending score and profession strongly influence segmentation.
- Combining supervised classification with clustering provides deeper marketing insights.
- Machine learning models can support scalable customer targeting strategies.

---

## 🛠️ Technologies Used
- R
- tidyverse
- caret
- ggplot2
- dplyr
- factoextra (PCA & clustering visualization)

---

## 🚀 Business Impact
The developed framework helps organizations:
- Identify customer behavior patterns
- Improve targeted marketing campaigns
- Personalize customer engagement strategies
- Support strategic decision-making using data analytics

---
