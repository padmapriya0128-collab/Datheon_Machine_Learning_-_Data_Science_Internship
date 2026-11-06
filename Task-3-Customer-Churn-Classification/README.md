# Customer Churn Prediction Using Machine Learning

## Project Overview
This project predicts whether a telecom customer is likely to leave a service using machine learning classification algorithms.

Customer churn prediction helps businesses identify customers who may discontinue their services and take appropriate retention measures.

## Internship
**Datheon – Machine Learning and Data Science Internship**

**Task 3: Customer Churn Prediction**

## Dataset
- Dataset: IBM Telco Customer Churn
- Records: 7,043 customers
- Target variable: `Churn`
- Target classes: Yes and No

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTENC)
- XGBoost
- Jupyter Notebook

## Project Workflow
1. Data loading and exploration
2. Data cleaning and missing-value handling
3. Exploratory Data Analysis (EDA)
4. Feature selection and preprocessing
5. Train-test splitting
6. Class imbalance handling using SMOTENC
7. Model training using Random Forest and XGBoost
8. Model evaluation using Accuracy, Precision, Recall, F1-score and ROC-AUC
9. Five-fold stratified cross-validation
10. Feature importance analysis

## Machine Learning Models
- Random Forest Classifier
- XGBoost Classifier

## Cross-Validation Results

| Model | Mean ROC-AUC |
|---|---:|
| Random Forest | 0.8163 |
| XGBoost | 0.8366 |

XGBoost achieved the higher mean cross-validation ROC-AUC in this experiment.

## Project Files
- `customer_churn_prediction.ipynb` – Complete analysis and model implementation
- `final_model_comparison.csv` – Model evaluation results
- `random_forest_feature_importance.csv` – Random Forest feature rankings
- `xgboost_feature_importance.csv` – XGBoost feature rankings
- `data/` – Dataset folder

## Conclusion
This project compares two machine learning classification algorithms for predicting telecom customer churn. Based on five-fold cross-validation, XGBoost achieved a higher mean ROC-AUC than Random Forest.

The project demonstrates data preprocessing, class imbalance handling, model training, evaluation and feature importance analysis.

## Author
**Padmaa Priya Y M**

B.Tech – Artificial Intelligence and Data Science
