# global_cost_of_living

Project Overview
This project focuses on analyzing the Global Cost of Living using various machine learning algorithms for feature selection and prediction. The main objective is to identify critical factors influencing the cost of living in different regions, build robust predictive models, and provide actionable insights. The project also includes a detailed data cleaning and preprocessing pipeline to ensure the highest data quality before model training.

Dataset Description
The dataset used for this project contains various economic indicators from different regions, influencing the cost of living. These indicators include housing prices, food costs, transportation expenses, and other cost factors.

Data Source: Global Cost of Living dataset (merged and cleaned from multiple sources)
Columns: Each column represents an economic factor (e.g., rent, food, utilities, etc.), and rows represent different geographical regions.
Target Variable: A continuous variable representing the overall cost of living index.
Data Quality Assessment
Ensuring high-quality data was paramount to the project's success. Below is a summary of the data quality assessment and the actions taken to enhance it:

Missing Values: The dataset had missing values in several columns, which were handled by imputing the median values to prevent loss of information and ensure model reliability.
Outliers: Identified using box plots, and transformations or scaling techniques were applied to minimize their impact on model accuracy.
Normalization: Features were scaled using StandardScaler and RobustScaler to bring them to a common scale, which is essential for some machine learning algorithms.
Multicollinearity Check: A correlation matrix was analyzed to detect multicollinearity. Features with high correlation were either dropped or combined to avoid redundancy and improve model efficiency.
Feature Selection: Statistically insignificant features were removed using p-values and recursive feature elimination, ensuring the model uses the most relevant predictors.
Modeling
We experimented with several classification models to predict the cost of living and evaluate feature importance:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors (KNN)
Naive Bayes Classifier
Gradient Boosting Classifier
Bagging Classifier
XGBoost Classifier
Hyperparameter Tuning: Models were tuned using GridSearchCV and RandomizedSearchCV to find the best combinations of hyperparameters for each algorithm.

Evaluation Metrics
The models were evaluated using the following metrics:

Accuracy Score
ROC-AUC Score
Confusion Matrix
Classification Report
Feature Importance
Random Forest and Logistic Regression were used to identify the most critical features influencing the cost of living, which were then visualized using bar plots. Feature importance values were sorted to highlight the most influential factors.

Key Outcomes
Identification of top cost-driving factors, providing actionable insights for decision-making.
High model accuracy with well-optimized machine learning algorithms.
Data preprocessing techniques ensured high-quality input for reliable predictions.
Visualizations
Feature Distributions: Histograms and density plots were used to visualize the distribution of each feature.
Model Performance: Confusion matrices and ROC curves were plotted to illustrate the models' performance.
Feature Importance: A bar plot displaying the most important features contributing to cost predictions.
Conclusion
This project provided a comprehensive analysis of the global cost of living, identifying critical factors and developing highly accurate predictive models. The results can help businesses and policymakers make informed decisions based on robust data insights. Data quality played a crucial role in achieving these results, with rigorous cleaning, scaling, and feature selection steps ensuring the best outcomes.
