# Loan Approval Analysis

## Introduction
This project provides a detailed analysis of a synthetic dataset related to credit risk and loan approval processes. The dataset was inspired by the original Credit Risk dataset on Kaggle and includes enriched features based on financial risk. By leveraging machine learning and data analysis techniques, this project explores the factors influencing loan approval.

---

## Dataset Overview

The dataset contains **45,000 records** and **14 variables** divided into categorical and continuous types. Below is an overview of the features:

| Column                         | Description                                         | Type         |
|--------------------------------|-----------------------------------------------------|--------------|
| `person_age`                   | Age of the person                                  | Float        |
| `person_gender`                | Gender of the person                               | Categorical  |
| `person_education`             | Highest education level                            | Categorical  |
| `person_income`                | Annual income                                      | Float        |
| `person_emp_exp`               | Years of employment experience                     | Integer      |
| `person_home_ownership`        | Home ownership status                              | Categorical  |
| `loan_amnt`                    | Loan amount requested                              | Float        |
| `loan_intent`                  | Purpose of the loan                                | Categorical  |
| `loan_int_rate`                | Loan interest rate                                 | Float        |
| `loan_percent_income`          | Loan amount as a percentage of annual income       | Float        |
| `cb_person_cred_hist_length`   | Length of credit history in years                 | Float        |
| `credit_score`                 | Credit score of the person                         | Integer      |
| `previous_loan_defaults_on_file` | Indicator of previous loan defaults               | Categorical  |
| `loan_status` (target variable)| Loan approval status: 1 = approved, 0 = rejected  | Integer      |

The dataset is structured for feature analysis and predictive modeling, making it suitable for testing classification algorithms.

---

## Project Detail
The details of the project can be found here [Loan Approval Analysis](https://github.com/perryfalcon0410/Loan-Approval-Analysis/blob/main/Loan_approval_analysis.ipynb)

## Project Workflow

### 1. Data Exploration

- Statistical summaries of numerical variables.
- Analysis of categorical distributions.
- Identifying missing values or data imbalances.
- Visualization of key trends using tools such as Matplotlib and Seaborn.

### 2. Data Cleaning and Preprocessing

- Handle missing values and outliers.
- One-hot encoding for categorical variables.
- Scaling and normalizing continuous features.
- Balancing the dataset using SMOTENC.

### 3. Exploratory Data Analysis (EDA)

- Feature correlation analysis.
- Insights into key predictors of loan approval.
- Visualizations to identify trends and anomalies.

### 4. Model Development and Evaluation

- Training models using logistic regression, decision trees, and ensemble methods.
- Tuning hyperparameters to improve accuracy.
- Evaluating model performance with Precision, Recall, F1-Score

---

## Usage

To run the project, ensure you have the following setup:

### Required Libraries
- Python 3.7+
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- imbalanced-learn

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repo/loan-approval-analysis.git
   cd loan-approval-analysis
   ```

2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Loan_approval_analysis.ipynb
   ```

4. Run each cell to follow the analysis and model-building process.

---

## Key Findings

- Individuals with higher credit scores do NOT have a greater likelihood of loan approval.
- The bank will likely give a loan for debt consolidation, home improvement, and medical intents.
- The younger generation is the bank's target, but the reject percentage is similar across all age groups.
- Balancing the dataset significantly improved model performance.

---

## Future Enhancements

- Extend the analysis by incorporating real-world data.
- Build a web application for real-time loan eligibility predictions.
- Investigate additional advanced ML algorithms like XGBoost or neural networks.

---

## Contributions
Contributions are welcome! Please submit pull requests or raise issues to improve this project.

---
