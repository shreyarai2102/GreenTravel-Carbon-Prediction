# Green Travel: Predicting High Carbon Business Trips Using Machine Learning

## Project Overview

This capstone project focuses on predicting whether a corporate business trip will result in high carbon emissions using Machine Learning. The project also includes Exploratory Data Analysis (EDA) and Process Mining to understand travel patterns, identify operational bottlenecks, and generate sustainability insights.

The final model, XGBoost, achieved excellent predictive performance and can help organizations make environmentally responsible travel decisions.

---

## Problem Statement

Business travel contributes significantly to carbon emissions. Organizations need intelligent systems to identify high-carbon trips before approval so that sustainable alternatives can be considered.

This project builds a machine learning model that predicts whether a business trip will be classified as High Carbon or Low Carbon based on travel-related information.

---

## Dataset

The project uses four datasets:

- Train Dataset – Historical business trip records with the target variable (`HighCarbon`)
- Test Dataset – Unseen business trip records for prediction
- Event Log Dataset – Business process event logs
- Event Attributes Dataset – Additional event-related information

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib
- GitHub

---

## Exploratory Data Analysis

EDA was performed to understand:

- High Carbon trip distribution
- Shipping type distribution
- Business unit analysis
- Purpose analysis
- Delay reasons
- Expense reimbursement
- Feature importance
- Trip duration
- Transportation changes

---

## Process Mining

Process mining techniques were applied to:

- Analyze travel workflows
- Discover common process variants
- Measure trip duration
- Identify process bottlenecks
- Analyze event frequencies

---

## Machine Learning Models

The following classification models were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

---

## Model Performance

| Model | Accuracy | ROC-AUC |
|--------|---------:|---------:|
| Logistic Regression | 77.22% | 0.8102 |
| Decision Tree | 98.73% | 0.9844 |
| Random Forest | ~99.17% | ~0.998 |
| **XGBoost** | **99.35%** | **0.99937** |

**Best Performing Model:** XGBoost

---

## Project Structure

```text
Green-Travel-Capstone-Project/
│
├── data/
├── notebooks/
├── images/
├── models/
├── submission/
├── report/
├── requirements.txt
├── README.md
└── LICENSE
```

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/<your-username>/Green-Travel-Capstone-Project.git
```

2. Install the required dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook in Google Colab or Jupyter Notebook.

4. Run all cells to reproduce the results.

---

## Key Results

- Performed data preprocessing and feature engineering.
- Conducted Exploratory Data Analysis and Process Mining.
- Compared four machine learning models.
- Selected XGBoost as the best-performing model.
- Generated predictions for the test dataset.

---

## Future Scope

- Deploy the model as a web application.
- Integrate Explainable AI (SHAP/LIME).
- Build an interactive dashboard using Streamlit or Power BI.
- Add real-time prediction capabilities.
- Explore deep learning approaches for further improvement.

