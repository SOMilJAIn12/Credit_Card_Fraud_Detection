# Credit Card Fraud Detection 

## Problem Statement
Credit card fraud is a serious financial issue where fraudulent transactions are extremely rare compared to genuine ones.  
The objective of this project is to build a machine learning model that can accurately detect fraudulent credit card transactions while handling severe class imbalance.



## Dataset
- Highly imbalanced dataset
- Fraudulent transactions are significantly fewer than normal transactions
- Features are PCA-transformed for confidentiality
- Source: Kaggle Credit Card Fraud Dataset

> Dataset is not included in this repository due to size limitations.  
> Please download the dataset from Kaggle and place it inside the `https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data` directory.



## Approach
- Exploratory Data Analysis (EDA)
- Feature Scaling
- Handling Imbalanced Dataset
- Model Training
- Hyperparameter Tuning
- Model Evaluation



## Models Used
- Logistic Regression
- Hyperparameter Tuning using RandomizedSearchCV
- Class Weight balancing to address class imbalance



## Evaluation Metrics
Accuracy is not suitable for imbalanced datasets. The following metrics were used:
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix



## Results
- The model effectively identifies fraudulent transactions
- Optimized to achieve high recall to reduce false negatives
- ROC-AUC used as the primary evaluation metric



## Tech Stack
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn



## Key Learnings
- Handling highly imbalanced datasets
- Importance of ROC-AUC over accuracy
- Hyperparameter tuning for real-world problems
- Building an end-to-end machine learning pipeline



## Author
Somil Jain

