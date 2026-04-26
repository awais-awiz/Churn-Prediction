# Customer Churn Prediction Using Machine Learning

## Overview
This project predicts telecom customer churn using supervised machine learning models on the IBM Telco Customer Churn dataset.  
The objective is to identify customers likely to leave and support customer retention strategies.

## Dataset
Dataset used: **IBM Telco Customer Churn**

Kaggle Dataset Link:  
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

**Note:**  
The dataset is not included in this repository due to licensing considerations.


## Features
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Class imbalance handling using SMOTE-Tomek
- Multiple model training and comparison
- Soft Voting Ensemble implementation
- Threshold tuning and error analysis
- Model evaluation with multiple performance metrics

## Models Implemented
- Random Forest
- XGBoost
- LightGBM
- Logistic Regression
- CatBoost
- Soft Voting Ensemble

## Evaluation Metrics
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Bootstrap Confidence Intervals

## Project Results
- Soft Voting Ensemble delivered the most balanced performance.
- Improved churn detection through threshold tuning and error analysis.
- Ensemble model achieved strong predictive stability.

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- CatBoost
- Matplotlib
- Seaborn
- Imbalanced-learn


## Project Structure

```bash
Customer-Churn-Prediction/
│
├── notebooks/
│   └── ChurnProject.ipynb
│
├── reports/
│   └── Project_Report.pdf
│
└── README.md
```

## Installation

Clone repository:

## Run the Project
Open:

```bash
notebooks/ChurnProject.ipynb
```

Run all cells sequentially.

## Future Improvements
- Hyperparameter optimization
- Deployment with Flask/Streamlit
- Explainable AI using SHAP
- Deep learning approaches for churn prediction

## Team
- [Awais Arif](https://github.com/username)
- [Maliha Fajar](https://github.com/username)
- [Afaq Imran](https://github.com/username)
- [Muhammad Abdullah Nadeem](https://github.com/username)
- [Hassan Zahid](https://github.com/username)

## License
This repository is for educational and research purposes.
