# Volve Oil Production Forecasting  
**SPE KSA Digital Energy Data Science Competition**

## Project Overview

This project develops a machine learning pipeline to forecast daily oil production (`BORE_OIL_VOL`) using historical well production and operational data from the **Volve oil field**.

Oil production forecasting is a critical task in reservoir engineering and field management. Accurate forecasts help engineers estimate reserves, plan production strategies, and support economic decision-making.

However, real-world production data rarely follows smooth decline curves. Production can fluctuate due to:

- reservoir pressure depletion  
- operational adjustments  
- multiphase flow behavior  
- measurement noise  

Because of this, forecasting production requires models that can capture **complex relationships while still preserving physically realistic production trends**.

The objective of this project is to build a machine learning model capable of predicting future oil production while maintaining realistic decline behavior.

---

# Dataset

The dataset contains historical operational and production measurements from wells in the **Volve field**.

Key variables include:

- Well operational measurements  
- Pressure and temperature data  
- Choke size  
- Production hours  
- Historical oil production (`BORE_OIL_VOL`)

The target variable for prediction is: BORE_OIL_VOL
#BORE_OIL_VOL

which represents the **daily oil production volume**.

---

# Project Workflow

The notebook follows a structured machine learning pipeline:

### 1. Problem Overview
Understanding the forecasting objective and domain constraints.

### 2. Initial Data Exploration
Inspecting dataset structure, missing values, and variable types.

### 3. Exploratory Data Analysis (EDA)

EDA includes:

- Production decline visualization  
- Target variable distribution  
- Correlation analysis  
- Identification of noisy or irrelevant variables  

### 4. Data Preprocessing

Data cleaning steps include:

- Handling missing values  
- Removing noisy features  
- Preparing the dataset for machine learning

### 5. Feature Engineering

Additional features were engineered to help the model capture production behavior:

- Time-based features  
- Well operational features  
- Production trend indicators

### 6. Model Training

Machine learning models were trained to predict daily oil production.

Model performance was evaluated using standard regression metrics.

### 7. Forecast Generation

The trained model is used to generate future production forecasts while maintaining physically realistic decline behavior.

### 8. Model Interpretation (Explainable AI)

Explainability methods were used to identify which features most influence production predictions.

This helps ensure the model's decisions align with **engineering intuition and domain knowledge**.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- SHAP (Explainable AI)

## Repository Structure

The repository contains the following files:

```
volve-oil-production-forecasting/
│
├── volve-oil-production-forecasting-spe-ksa.ipynb
├── README.md
└── oil_production_forecast.csv.csv
```

# Results

The developed model successfully learns production behavior patterns from historical data and generates realistic production forecasts.

The approach demonstrates how machine learning can support **data-driven reservoir management and production planning**.

---

# Author

**Mayar Mousa**

University of Jeddah  
Data Science 
