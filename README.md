Algerian Forest Fire Prediction
Overview

This project focuses on predicting the Fire Weather Index (FWI) using the Algerian Forest Fires dataset. The notebook demonstrates a complete machine learning workflow, including data preprocessing, exploratory analysis, feature engineering, scaling, and regression model comparison.

The primary goal is to evaluate different linear regression-based algorithms and determine which model provides the most accurate predictions for wildfire risk assessment.

Dataset

The project uses the Algerian Forest Fires Dataset, which contains meteorological and environmental attributes related to forest fire occurrences.

Features
Temperature
Relative Humidity (RH)
Wind Speed (Ws)
Rain
FFMC
DMC
DC
ISI
BUI
Classes (Fire / Not Fire)
Target Variable
FWI (Fire Weather Index)
Project Workflow
1. Data Preprocessing
Load dataset using Pandas
Remove unnecessary date columns
Convert categorical fire classes into numerical values
2. Feature Engineering
Split data into training and testing sets
Analyze feature correlations
Remove highly correlated features to reduce multicollinearity
3. Feature Scaling
Apply StandardScaler to standardize feature values
4. Model Training

The following regression models are implemented:

Linear Regression
Lasso Regression
LassoCV
Ridge Regression
RidgeCV
Elastic Net
ElasticNetCV
5. Model Evaluation

Models are evaluated using:

Mean Absolute Error (MAE)
R² Score
Actual vs Predicted scatter plots
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Jupyter Notebook
Results

The notebook compares multiple regularized regression techniques and evaluates their effectiveness in predicting the Fire Weather Index (FWI). Cross-validation methods such as RidgeCV, LassoCV, and ElasticNetCV are used to optimize model performance.

Learning Outcomes
Data preprocessing and cleaning
Correlation-based feature selection
Feature scaling using StandardScaler
Regularization techniques (L1, L2, Elastic Net)
Regression model evaluation and comparison
Building an end-to-end machine learning pipeline
Future Improvements
Hyperparameter tuning using GridSearchCV
Advanced ensemble models (Random Forest, XGBoost)
Deployment using Flask/FastAPI
Interactive dashboard for wildfire risk prediction
Author

Krishna Khajuria
Machine Learning & Data Science Enthusiast
