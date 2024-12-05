# Credit Card Fraud Detection Project

Welcome to my **Credit Card Fraud Detection** project!

This project focuses on building a machine learning model using the **Random Forest Classifier** to detect fraudulent credit card transactions. The objective is to classify transactions as either **Fraud** or **Not Fraud** based on various features such as transaction amounts, times, and anonymized features.

### Project Overview

The dataset used in this project contains credit card transaction records, with labels indicating whether each transaction was fraudulent or not. We employ the **Random Forest Classifier** to train the model and evaluate its performance using various metrics such as **ROC-AUC** and the **Confusion Matrix**.

This project walks through the entire process of data preprocessing, model training, and evaluation, and aims to provide an accurate fraud detection system.

### Key Steps in the Project:

1. **Data Preprocessing**: 
   - Data cleaning, feature engineering, and handling missing or irrelevant data.
   - Splitting the data into training, validation, and test sets.

2. **Model Training**: 
   - Using **Random Forest Classifier** to predict fraudulent transactions.
   - Setting model parameters and training on the training data.

3. **Model Evaluation**:
   - Evaluating the model performance with metrics like **ROC-AUC**, **Confusion Matrix**, and analyzing **Type I** and **Type II** errors.

4. **Feature Importance**:
   - Analyzing the importance of each feature in predicting fraudulent transactions using the Random Forest model.

### Dataset

The dataset for this project is located in the `data/` folder. It contains anonymized credit card transaction data used to train and test the fraud detection model.

### Requirements

This project requires the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- scikit-learn

You can install all dependencies by running:

```bash
pip install -r requirements.txt
