# Fraud Detection Project

## **Overview**
Detect fraudulent credit card transactions using an imbalanced dataset. We balance the data and train a model to predict fraud.

## **Data**
- **V1 to V28**: Anonymized features
- **Time**: Time since the first transaction
- **Amount**: Transaction amount
- **Class**: 0 = non-fraud, 1 = fraud

## **Problem**
The dataset has more non-fraudulent transactions than frauds, leading to biased predictions.

## **Solution**
- **Undersampling**: Reduce non-fraud cases to match the number of fraud cases.
- **Train Model**: Use the balanced dataset to train and predict fraud.
