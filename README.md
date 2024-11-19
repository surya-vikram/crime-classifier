# Crime Cast: Forecasting Crime Categories 🕵️‍♂️🔍

## Overview
This project is a submission to the **[Kaggle Crime Cast Forecasting](https://www.kaggle.com/competitions/crime-cast-forecasting-crime-categories)** competition. The goal is to develop machine learning models that accurately predict crime categories based on a rich dataset encompassing detailed information about criminal incidents.

The dataset includes:
- **Location Features**: Where crimes occurred.
- **Date-Time Features**: When crimes happened.
- **Victim & Crime Attributes**: Specific incident details like demographics, weapons used, and premises.

This analysis aims to assist in predicting crime categories and provide insights for improving public safety strategies.

---

## Steps Undertaken
### 1. Importing Libraries
Used essential libraries for data manipulation, visualization, and machine learning, including pandas, matplotlib, seaborn, scikit-learn, XGBoost, and TensorFlow.

### 2. Loading Data
Loaded and explored the dataset to understand its structure, distribution, and potential challenges like missing values or imbalanced data.

### 3. Exploratory Data Analysis (EDA)
Performed a comprehensive analysis of the dataset, exploring:
- **Location and Area Trends**: Identifying hotspots for criminal activities.
- **Date-Time Analysis**: Examining patterns like seasonal or hourly spikes.
- **Victim and Crime Features**: Studying demographic impacts and types of crimes.
- **Weapons and Premises**: Analyzing the relationship between tools used, premises, and crime types.

### 4. Preprocessing
- Cleaned data by handling missing values and outliers.
- Encoded categorical variables using one-hot or label encoding.
- Normalized and scaled features for better model performance.

### 5. Model Training and Selection
Trained multiple machine learning models, evaluated their performance, and selected the best-performing ones. Key steps included:
- Splitting data into train-validation sets.
- Building helper functions for modular and efficient training.
- Training various models:
  - **Logistic Regression**
  - **K-Nearest Neighbors**
  - **Support Vector Classifier**
  - **Decision Tree**
  - **Random Forest** (Bagging)
  - **XGBoostClassifier** (Boosting)
  - **Multi-Layer Perceptron** (Neural Networks)

### 6. Ensemble Models
- Combined predictions using ensemble techniques:
  - **Voting Classifier**:
    - Hard and soft voting strategies.
  - **Stacking Classifier**: Leveraging multiple models for better accuracy.

### 7. Model Comparison
- Compared models based on metrics like accuracy, F1-score, and ROC-AUC.
- Visualized results using:
  - ROC curves
  - Confusion and error matrices.

### 8. Submission
Prepared the final predictions and submitted them to Kaggle for evaluation.

---

## Results
- **Best Model**: [Insert your best-performing model here, e.g., XGBoostClassifier]
- **Key Metrics**: [Mention relevant metrics like accuracy, F1-score, or ROC-AUC]
- **Ensemble Performance**: Highlight how ensemble methods improved performance over standalone models.
