#  Customer Churn Prediction Using XGBoost

A Machine Learning project that predicts customer churn using the **XGBoost Classifier**.

##  Project Overview
This project demonstrates an end-to-end machine learning workflow:
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training using XGBoost
- Model Evaluation

##  Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

##  Model Performance

| Metric | Value |
|--------|------:|
| Accuracy | **76.72%** |
| ROC-AUC Score | **0.8576** |
| Precision (Churn) | **0.54** |
| Recall (Churn) | **0.80** |
| F1-Score (Churn) | **0.65** |

### Classification Report

| Metric | Class 0 | Class 1 |
|--------|:-------:|:-------:|
| Precision | **0.91** | **0.54** |
| Recall | **0.75** | **0.80** |
| F1-Score | **0.83** | **0.65** |

##  Key Insights

- Overall Accuracy: **76.72%**
- ROC-AUC Score: **0.8576 (Very Good)**
- Top predictive features:
  - MonthlyCharges
  - TotalCharges
  - Tenure

##  Installation

```bash
pip install -r requirements.txt
```

Run the notebook in Jupyter Notebook or Google Colab.

##  Author

**Arijit Dasgupta**

Data Analyst | Machine Learning Enthusiast
