# California Housing Price Prediction
This project aims to predict housing prices in California using machine learning models and data from the 1990 California census. The project covers the full machine learning pipeline, including data preprocessing, feature engineering, handling skewness, and evaluating models.

# Project Workflow:
<img src="Cream Green Pink Flow Chart Graph.png" alt="Description" >
## Data Preprocessing:

* Handled missing values and outliers.
* Processed the ocean_proximity categorical feature with appropriate encoding.
* Standardized and normalized numerical features for better model performance.
## Feature Engineering:

* Created new features based on domain knowledge to improve model accuracy.
* Treated skewness in the data using various transformations (Log, Square Root, Box-Cox, etc.) to ensure normal distribution of features.
* Machine Learning Models: Implemented and compared the performance of 10 different machine learning models:

1. MLP Regressor
2. Support Vector Regressor (SVR)
3. Linear Regression
4. Decision Tree Regressor
5. Random Forest Regressor
6. Extra Trees Regressor
7. Gradient Boosting Regressor
8. KNeighbors Regressor
9. XGBoost Regressor
10. CatBoost Regressor
## Model Evaluation:

Evaluated models using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² score.
Performed cross-validation to ensure the robustness of the models and prevent overfitting.
## Tools & Libraries:
* Languages: Python
* Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, XGBoost, CatBoost
## Key Highlights:
* Comprehensive data preprocessing and feature engineering steps.
* Addressed skewness in data distribution.
* Comparison of 10 machine learning models to find the best-performing model for predicting housing prices.
* This project provides a full end-to-end solution for building and optimizing machine learning models for real estate price prediction in California.
