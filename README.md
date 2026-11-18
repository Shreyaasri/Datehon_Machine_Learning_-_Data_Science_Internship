# Real Estate Housing Price Prediction Using Ridge and Lasso Regression

## Project Overview
This project uses the California Housing dataset to predict median house values using machine learning regression techniques.

## Objectives
- Explore and preprocess housing data.
- Handle missing values.
- Perform correlation analysis.
- Create interaction features.
- Train OLS, Ridge, and Lasso Regression models.
- Optimize Ridge and Lasso using GridSearchCV.
- Evaluate models using RMSE, MAE, and R² score.
- Visualize actual vs. predicted prices and residuals.

## Dataset
**File:** `california_housing.csv`

The dataset contains housing and demographic information, including median income, housing age, rooms, bedrooms, population, households, geographical coordinates, and ocean proximity.

**Target variable:** `median_house_value`

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Models Implemented
1. OLS Linear Regression
2. Ridge Regression
3. Lasso Regression

GridSearchCV is used to tune the regularization parameter (`alpha`) for Ridge and Lasso.

## Evaluation Metrics
- **RMSE:** Root Mean Squared Error
- **MAE:** Mean Absolute Error
- **R² Score:** Coefficient of determination

## Visualizations
- Correlation heatmap
- Actual vs. Predicted House Prices
- Residual Plot
- Model Performance Comparison

## Project Files
- `housing_price_prediction.ipynb` — Complete analysis, model training, evaluation, and visualizations.
- `california_housing.csv` — Dataset used in the project.
- `README.md` — Project documentation.

## Conclusion
The project demonstrates housing price prediction using linear regression and regularization techniques. The models are compared using evaluation metrics to understand their predictive performance.