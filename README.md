DEFAULT OF CREDIT CARD CLIENTS DATASET - CLASSIFICATION : MODEL BUILDING AND MACHINE LEARNING APPROACH

Objectives
To develop a predictive model that estimates the likelihood of credit card default among clients based on demographic and financial attributes. The goal is to identify key risk factors influencing default behavior, improve credit risk.Also to Predicts whether a client is likely to default on their credit card payment.To provides actionable insights to optimize credit approval strategies and reduce financial load.
This project focuses on detecting fraudulent credit card transactions using Machine Learning.
The dataset is sourced from the UCI Repository and contains anonymized credit card transactions with class labels:

0 → Legitimate Transaction

1 → Fraudulent Transaction

The goal is to train models that can classify transactions as fraud or non-fraud with high accuracy while handling class imbalance.

⚙️ Technologies Used

- Python 🐍

- Pandas, NumPy (Data Handling)

- Matplotlib, Seaborn (Visualization)

- Scikit-learn (ML Models)

📈 Methodology

- Exploratory Data Analysis (EDA)

- KDE Plots, Count Plots, Heatmaps

- Insights on payment/bill amounts, target distribution

- Data Preprocessing

- Handling missing values

- Encoding categorical variables (OneHotEncoder / Label Encoding)

- Feature scaling

- Feature Selection

- SelectKBest (ANOVA F-test)

- Correlation analysis

- Model Training & Evaluation

- Evaluation metrics: Accuracy, Precision, Recall, F1-Score

- Class Imbalance Handling

- SMOTE (Synthetic Minority Over-sampling Technique)

- Model Deployment

- Final trained model saved as model.joblib

- Imbalanced-learn (SMOTE for imbalance handling)

- Joblib (Model Saving)
