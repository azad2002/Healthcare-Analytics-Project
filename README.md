# Healthcare-Analytics-Project
Developed a machine learning model to predict hospital readmissions for diabetes patients using the UCI Diabetes 130-US Hospitals dataset (100K+ records). Performed data cleaning, feature engineering, and exploratory analysis, and trained classification models to identify key factors influencing patient readmission risk.



# Predicting Hospital Readmissions for Diabetes Patients

A machine learning project that predicts whether diabetic patients will be readmitted to the hospital within 30 days using healthcare data from 130 U.S. hospitals.

This project demonstrates a complete data science workflow including:

Data acquisition

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Feature engineering

Machine learning modeling

Model evaluation

The goal is to help hospitals identify high-risk patients early and improve healthcare outcomes while reducing medical costs.

# Dataset

Source:
UCI Machine Learning Repository

Dataset:
Diabetes 130-US Hospitals for Years 1999–2008

 https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008

 # Dataset Characteristics
Feature	Description
Total Records	101,766 hospital admissions
Features	~50 clinical and administrative variables
Time Period	1999 – 2008
Hospitals	130 US hospitals
Target Variable	Readmission status
Target Classes
# Label	Meaning
<30	Readmitted within 30 days
>30	Readmitted after 30 days
NO	No readmission
 # Project Objective

Hospital readmissions are expensive and often preventable.

This project aims to:

Identify patients at risk of early readmission

Analyze clinical and demographic factors influencing readmission

Build a predictive machine learning model

Provide insights for hospital resource optimization

# Technologies Used
# Category	 # Tools
Programming	  Python
Data Processing	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Machine Learning	Scikit-learn
Notebook	Jupyter
Version Control	Git & GitHub
# Project Structure
diabetes-readmission-prediction/
│
├── data/
│   └── diabetic_data.csv
│
├── notebooks/
│   └── Predicting Hospital Readmissions for Diabetes Patients.ipynb
│
├── images/
│   └── charts and visualizations
│
├── README.md
│
└── requirements.txt
# Project Workflow
 # 1️ Data Acquisition

Dataset downloaded from the UCI Machine Learning Repository.

Contains patient data including:

Demographics

Diagnoses

Medications

Procedures

Hospital stay information

# 2️ Data Cleaning

Key preprocessing steps:

Handling missing values

Removing duplicate records

Converting categorical variables

Dropping irrelevant columns

# 3️ Exploratory Data Analysis (EDA)

EDA was performed to understand:

Patient demographics

Distribution of diagnoses

Medication usage

Readmission trends

Example insights explored:

Age distribution of patients

Relationship between number of diagnoses and readmission

Impact of hospital stay duration

Visualizations include:

Bar charts

Heatmaps

Distribution plots

Correlation analysis

# 4️ Feature Engineering

Key features engineered:

Number of medications

Number of procedures

Number of diagnoses

Patient age groups

Categorical variables were encoded using:

Label encoding

One-hot encoding

# 5️ Machine Learning Models

Several models were explored for prediction:

Logistic Regression

Decision Tree

Random Forest

Gradient Boosting

Models were trained using Scikit-Learn.

# 6️ Model Evaluation

Models were evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

The best performing model was selected based on overall predictive performance and interpretability.

# Key Insights

Some insights derived from the analysis:

Patients with higher number of diagnoses show higher readmission rates.

Frequent hospital visits correlate strongly with readmission probability.

Certain age groups have higher risk levels.

Medication complexity may contribute to readmission risk.

#  Requirements

Example dependencies:

pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
# Future Improvements

Possible extensions of this project:

Deep learning models

Feature importance analysis

Model explainability (SHAP / LIME)

Deployment using Streamlit

Real-time prediction API
