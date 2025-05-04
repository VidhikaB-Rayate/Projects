# Food Price Prediction – Machine Learning (Python)

## Project Overview

This project focuses on predicting food prices across different states and years using historical data. The goal is to build a machine learning model to forecast food prices based on various features like year, state, category, and commodity. The project also aims to help stakeholders make better market decisions based on predicted trends.

---

## Technologies Used

- Python  
- Scikit-Learn  
- Pandas  
- Matplotlib  
- Colab Notebook  

---

## Data Preprocessing

1. **Data Cleaning**: Handled missing values and removed irrelevant columns.  
2. **Feature Encoding**: Converted categorical variables (like state, category, commodity) into numerical features using one-hot encoding.  
3. **Multicollinearity Check**: Used Variance Inflation Factor (VIF) to detect multicollinearity among features.  
4. **Feature Scaling & Dimensionality Reduction**: Applied **StandardScaler** for feature scaling and **PCA (Principal Component Analysis)** to reduce dimensionality and address multicollinearity issues while preserving essential data patterns.

---

## Machine Learning Models

Several models were tested to find the best one for predicting food prices:

- **Linear Regression**  
- **Decision Tree Regressor**  
- **Random Forest Regressor**

**Hyperparameter Tuning**:  
GridSearchCV was used to tune model hyperparameters and select the best combination.

---

## 📌 Model Evaluation

The models were evaluated using **train** and **test** scores. The **Random Forest Regressor** gave the best performance with high accuracy and minimal overfitting, showing consistent results on both train and test data.

After applying StandardScaler and PCA, the model successfully handled multicollinearity issues and improved its ability to make reliable predictions for future years as well.

---

## 📌 How This Model Helps in Decision-Making

- **Forecasting Food Prices**: Predicts future commodity prices across different states, months, and years, helping identify trends in advance.  
- **Market Planning**: Assists government bodies, traders, and retailers in procurement, stock management, and pricing decisions.  
- **Insight Generation**: Reveals regional price variations and commodity-specific trends, improving overall market strategy and risk management.

---

