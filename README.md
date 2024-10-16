# Project Overview
- **Objective:** Analyze the Global Cost of Living using machine learning for feature selection and prediction.
- **Goal:** Identify key factors influencing the cost of living and provide actionable insights through predictive models.
- **Data Pipeline:** Includes comprehensive data cleaning and preprocessing to ensure high-quality input before model training.

# Dataset Description
- **Source:** Merged and cleaned from multiple sources.
- **Columns:** Economic factors like housing, food, transportation, etc.
- **Target Variable:** Overall cost of living index.

# Data Quality Assessment
- **Missing Values:** Imputed using median values.
- **Outliers:** Handled via transformations and scaling techniques.
- **Normalization:** StandardScaler and RobustScaler were used.
- **Multicollinearity Check:** Correlation analysis to remove redundant features.
- **Feature Selection:** P-values and recursive elimination to keep the most relevant features.

# Modeling
- **Algorithms Used:**
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
  - K-Nearest Neighbors (KNN)
  - Naive Bayes
  - Gradient Boosting, Bagging, XGBoost
- **Hyperparameter Tuning:** GridSearchCV and RandomizedSearchCV used for optimization.

# Evaluation Metrics
- Accuracy Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report

# Feature Importance
- Identified using Random Forest and Logistic Regression.
- Visualized through bar plots.

# Key Outcomes
- Identification of top cost-driving factors.
- High model accuracy achieved with tuned algorithms.
- Data preprocessing ensured high-quality predictions.

# Visualizations
- Feature distributions, confusion matrices, ROC curves, and feature importance plots.

# Conclusion
- Provided insights into global cost-of-living factors.
- Reliable models for cost prediction, emphasizing data quality and preprocessing.
