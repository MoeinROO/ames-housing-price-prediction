# ames-housing-price-prediction
Predicting house prices using Linear and Polynomial Regression. This project demonstrates the significant impact of data preprocessing (Outlier removal, SMOTE, Encoding) on model accuracy.

Ames Housing Price Prediction: The Power of Preprocessing
This project explores the Ames Housing Dataset to predict residential home prices. The core objective is to demonstrate how systematic data cleaning and feature engineering can drastically improve the performance of Regression models.

📊 Project Overview
I compared two different approaches to evaluate the impact of data quality on machine learning outcomes:

Baseline Approach: Using raw numerical data with minimal cleaning.
Optimized Approach: Implementing advanced preprocessing techniques like outlier detection and categorical encoding.


🛠 Workflow & Methodology
1. Exploratory Data Analysis (EDA)
Used df.info() to identify numerical vs. categorical features.
Generated a Correlation Matrix to identify the features with the strongest impact on house prices (e.g., Square Footage, Overall Quality).
Visualized distributions and statistical summaries.
2. Preprocessing Pipeline (The Game Changer)
To improve the model, I implemented:

Missing Value Imputation: Handled nulls using Mean (for numerical) and Mode (for categorical) values.
Outlier Removal: Used the Interquartile Range (IQR) method to remove noise from the dataset.
Categorical Encoding: Applied One-Hot Encoding to convert neighborhoods and features like Central Air into machine-readable format.
Feature Scaling: Used StandardScaler to normalize feature ranges.
3. Models Implemented
Linear Regression
Multiple Regression (Adding more dimensions to the feature space)
Polynomial Regression (Capturing non-linear relationships)

Conclusion: Preprocessing reduced the Mean Squared Error (MSE) by approximately 79.41%, proving that “Data is the Fuel, but Preprocessing is the Engine.”

Developed as part of my Machine Learning Portfolio - Moein Roshan

:::
