# Medical_Cost_Prediction

Project With Use Of Python Code In Jupyter Notebook For Medical Cost Prediction

This file is a Jupyter Notebook for a machine learning project focused on predicting individual medical costs using patient data. The main goal of the project is to demonstrate a complete data science workflow: data loading, preprocessing, model building, and evaluation using a real-world-inspired dataset of patient details and healthcare expenditure.

# Project Description :-->

The notebook imports a medical insurance dataset containing various patient features such as age, gender, BMI, smoking status, region, medical history, daily exercise, annual income, insurance premium, blood pressure, cholesterol, chronic diseases, recent hospital visits, stress level, and the actual medical costs. It then follows these main steps:

Data Preprocessing: Separates features and target (Medical Costs), identifies categorical and numerical columns, and constructs a preprocessing pipeline with standard scaling for numerical data and one-hot encoding for categorical variables.

Model Pipeline: Constructs a machine learning pipeline using RandomForestRegressor to predict medical costs. The pipeline ensures all preprocessing and modeling steps are reproducible.

Training and Evaluation: Splits the data into training and test sets, fits the pipeline, then evaluates predictions with metrics like Mean Squared Error (MSE) and R² score. The final model achieves high predictive accuracy (R² ≈ 0.94 on the test set).

# Key Features:-->

End-to-end workflow: Data ingestion, preprocessing, feature engineering, modeling, and evaluation in one notebook.

Robust pipeline using Scikit-learn's Pipeline and ColumnTransformer for seamless and reproducible data science processes.

Uses a real-life healthcare scenario, making it relevant for both beginner and intermediate data science practitioners.

Clear presentation of results and model performance metrics.
