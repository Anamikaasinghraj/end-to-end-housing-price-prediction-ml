# 🏠 End-to-End Housing Price Prediction (Machine Learning)
<p align="center"> <img src="IFYOUF~1.JPG" width="800"> </p>

📌 Project Overview

This project implements a complete machine learning pipeline to predict residential property prices using regression and boosting algorithms.

The workflow follows an industry-standard approach including:

Data cleaning and preprocessing

Feature engineering

Cross-validation model comparison

Hyperparameter tuning

Model performance evaluation and error analysis

📊 Dataset

House Prices – Advanced Regression Techniques
Source: Kaggle

🔎 Exploratory Data Analysis
Correlation Heatmap
<p align="center"> <img src="Screenshot 2026-02-13 182942.png" width="700"> </p>

Key Insights:

Median Income shows strong positive correlation with house value.

Total Rooms, Bedrooms, and Households are highly correlated.

Location variables (latitude & longitude) influence pricing patterns.

⚙️ Machine Learning Pipeline
1️⃣ Data Preprocessing

Missing value imputation (median & most frequent)

One-hot encoding of categorical features

Feature scaling of numerical variables

Implemented using ColumnTransformer and Pipeline.

2️⃣ Feature Engineering

Derived additional ratio-based features

Removed redundant columns

Improved predictive performance through transformations

3️⃣ Model Comparison (Cross-Validation)

Models evaluated using K-Fold Cross Validation:

Linear Regression

Ridge Regression

Lasso Regression

Random Forest Regressor

HistGradientBoosting Regressor

Evaluation Metrics:

RMSE

MAE

R² Score

🛠 Tech Stack

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

👤 Author

Anamika Singh Raj
Aspiring Data Analyst / Machine Learning Engineer

