# Food Price Prediction – Machine Learning (Python)

## Project Overview

This project focuses on predicting food prices across different states and years using historical data. The goal is to build a machine learning model to forecast food prices based on various features like year, state, category, and commodity.

## Technologies Used

- Python
- Scikit-Learn
- Pandas
- Matplotlib
- Colab Notebook

## Data Preprocessing

1. **Data Cleaning**: Handled missing values and removed irrelevant columns.
2. **Feature Encoding**: Converted categorical variables (like state, category, commodity) into numerical features using one-hot encoding.

## Machine Learning Models

Several models were tested to find the best one for predicting food prices:

- **Linear Regression**
- **Lasso Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**

**Hyperparameter Tuning**: GridSearchCV was used to tune model hyperparameters and select the best combination.

## Model Evaluation

The models were evaluated using **train** and **test** scores. The **Decision Tree Regressor** gave the best performance with high accuracy and minimal overfitting, showing consistent results on both train and test data.

## Future Work

- **Power BI Integration**: Predictions will be visualized in Power BI for better reporting and insights.
- **Further Improvements**: Explore additional features and models to improve predictions.


