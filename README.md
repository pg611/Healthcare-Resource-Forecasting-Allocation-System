# Healthcare-Resource-Forecasting-Allocation-System
A data-driven project designed to predict hospital resource demand and optimize allocation strategies using machine learning and visualization tools. The system aims to help healthcare administrators make informed decisions to prevent both resource shortages and over-preparation.

# Problem Statement
Hospitals often struggle with either under-utilization or shortages of critical resources like beds, staff, and equipment due to unpredictable patient demand. This project forecasts future resource needs based on historical patient data, enabling proactive planning.

# Objectives
* Forecast hospital admissions and length of stay using machine learning models
* Allocate resources such as ICU beds and ventilators based on predicted demand
* Provide interactive visual dashboards to support administrative decisions
* Simulate real-life hospital scenarios to test model effectiveness

# Tech Stack
Languages: Python

Libraries: pandas, numpy, scikit-learn, XGBoost, matplotlib, seaborn

Visualization: Tableau

Machine Learning Models: Random Forest, XGBoost, Linear Regression

Tools: Jupyter Notebook, Excel

# Approach
# Data Cleaning & Preprocessing

* Handled missing values, normalized data, and encoded categorical features
* Feature engineering on time-based data (seasonality, holidays)

# Exploratory Data Analysis (EDA)

* Visualized patient trends by department, season, and region
* Identified correlations between demographics and resource needs

# Model Development

* Trained models to predict daily/weekly patient volumes
* Used regression techniques to forecast average length of stay
* Validated with RMSE and R² scores

# Resource Optimization

* Developed logic to estimate optimal number of beds, staff, and equipment
* Created breakeven analysis and scenario-based planning outputs

# Results
* Achieved R² of 0.85 in predicting patient admissions
* Reduced forecast error by ~18% compared to historical average methods
* Enabled hospitals to plan resource allocation 2 weeks in advance
* Visual dashboard helped stakeholders identify peak demand periods
