**Telco Customer Churn Prediction — End-to-End Analytics Project**

*Predictive Analytics | Machine Learning | EDA | XGBoost | Power BI Dashboard*

This project implements a complete customer churn prediction system for a telecom company, including data preprocessing, exploratory data analysis, machine-learning model development, evaluation, and visualization. It was developed as part of the HEPro Business Analytics Internship (2025).

📂 Repository Structure
│── Telco_churn.ipynb          # Jupyter Notebook containing full ML pipeline  
│── Project Report.pdf         # Detailed 14-page project documentation  
│── README.md                  # Project overview


📄 Project Overview

The goal of this project is to predict which customers are most likely to churn and identify key drivers behind churn behavior.
The final model (XGBoost) achieves:

✅ AUC ≈ 0.87
✅ Strong balance of precision & recall
✅ Clear business insights for customer retention

The entire workflow — from data cleaning to Power BI dashboarding — is implemented and explained in detail.

⚙️ Key Features
1️⃣ Data Preprocessing

Handling missing values

Converting TotalCharges to numeric

Encoding binary/multi-class categoricals

Scaling numeric features

Stratified train-test split (80/20)

2️⃣ Exploratory Data Analysis

Includes churn trends by:

Contract type

Tenure

Monthly charges

Internet service

Payment method

Visuals like correlation heatmaps, boxplots, and distribution charts are included in the notebook and PDF.

3️⃣ Model Development

Trained multiple models:

Logistic Regression

Random Forest

XGBoost (final model)

Hyperparameters tuned for class imbalance and performance.

4️⃣ Model Evaluation

Metrics compared:

Accuracy

Precision

Recall

F1 Score

ROC–AUC

XGBoost provided best AUC and recall balance.

5️⃣ Power BI Dashboard

Exported processed dataset for dashboarding, including:

Churn segmentation

Contract-level churn

Payment behavior

High-risk customer segments

📁 Files Description
📘 Telco_churn.ipynb

End-to-end machine-learning pipeline covering:

Data cleaning

Feature engineering

Visualizations

Model training & tuning

SHAP explainability

Final deployment-ready output

📄 Project Report.pdf

A professional 14-page report containing:

Executive summary

Business context

Project goals

Weekly log

EDA findings

Model comparison

Dashboard screenshots

Recommendations

🚀 How to Run the Project

Clone the repo

git clone https://github.com/your-username/Telco-Churn-Prediction.git


Install dependencies

pip install -r requirements.txt


Launch Jupyter Notebook

jupyter notebook


Open Telco_churn.ipynb and run all cells.

🧠 Key Insights

Tenure is the strongest churn indicator

Month-to-Month customers show highest churn

Electronic Check users have high churn risk

Add-ons (Tech Support/Security) reduce churn

Long-term contracts lead to more loyal users

📊 Dashboard Preview

(Power BI screenshots and charts are included inside the report.)

📌 Tech Stack

Python

Pandas, NumPy

Scikit-Learn

XGBoost

Matplotlib, Seaborn

Power BI
