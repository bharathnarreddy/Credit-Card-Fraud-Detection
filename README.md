# Credit-Card-Fraud-Detection

## Overview
This project builds a **fraud detection model** using **machine learning** techniques. It identifies fraudulent credit card transactions based on transaction data.

## Dataset
- **Source:** [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Features:**
  - **V1 - V28**: Principal Component Analysis (PCA) transformed features.
  - **Amount**: Transaction amount.
  - **Time**: Time elapsed from the first transaction.
  - **Class**: (0 = Legitimate, 1 = Fraud).

## Features
- Data Preprocessing (Handling Imbalanced Data, Scaling)  
- Feature Engineering (PCA, Correlation Analysis)  
- Model Training (Random Forest, Logistic Regression, Neural Networks)  
- Performance Metrics (Precision, Recall, F1-score)

## Usage
 1. Clone the Repository
    git clone https://bharathnarreddy/Credit-Card-Fraud-Detection.git
 2. Navigate to the Project Directory
    cd Credit-Card-Fraud-Detection
 3. Install the Necessary Dependencies
    pip install -r requirements.txt
 4. Run the Jupyter Notebook
    jupyter notebook notebooks/Fraud_Detection.ipynb

## Contributions
Contributions to **Credit-Card-Fraud-Detection** are welcome! If you'd like to enhance the fraud detection model, improve feature engineering, or optimize performance, feel free to fork the repository and submit a pull request.



