# EV-Registrations-2025-Project
EV data analysis for internship task
Project Title:
EV Charging Demand Prediction
Project Description:
This project focuses on forecasting the demand for electric vehicle (EV) charging stations using historical data and machine learning techniques. The goal is to help city planners, energy providers, and EV infrastructure companies make informed decisions about resource allocation and station placement.
Objectives:
Analyze historical EV charging usage data.

Identify key factors affecting charging demand (e.g., weather, time, location).

Build predictive models to forecast short-term and long-term EV charging demand.

Provide visualizations and insights to support data-driven planning.
 Folder Structure:
bash
Copy
Edit
EV-Charging-Demand-Prediction/
│
├── data/               # Raw and processed data
├── notebooks/          # Jupyter notebooks for EDA and modeling
├── src/                # Python scripts for data processing and modeling
├── models/             # Saved trained models
├── results/            # Plots, evaluation metrics, and reports
└── README.md           # Project documentation (this file)
Technologies Used
Languages: Python, SQL

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, XGBoost, statsmodels

Tools: Jupyter Notebook, Git, Excel

Environment: Google Colab / VS Code

Data Description:
Source: [Mention data source – open data portal, company-internal, synthetic, etc.]

Features:

Timestamps (hour, day of week, etc.)

Charging station ID

Location (lat-long or region)

Number of charging sessions

Energy consumed

Weather (temperature, rainfall, etc.)

Methodology:
Data Preprocessing:

Handling missing values

Feature engineering (e.g., time-based features)

Normalization

Exploratory Data Analysis (EDA):

Demand trends over time

Correlation with weather and time of day

Modeling:

Linear Regression

Random Forest Regressor

XGBoost

Time series models (ARIMA/SARIMA)

Evaluation using RMSE, MAE

Visualization:

Demand heatmaps

Time series forecasts

Feature importance
Key Results:
Best model: [e.g., XGBoost Regressor]

RMSE: [Insert Value]

MAE: [Insert Value]

Model showed strong accuracy in predicting hourly demand up to 24 hours ahead.
Submitted By:
Name: Divya Chand Chilla

Internship Program: AICTE Internship 2025

Week: Week 1






