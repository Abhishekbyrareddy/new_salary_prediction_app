# Salary Prediction Using Machine Learning

## Overview
This project predicts employee salaries using machine learning models based on features such as **Age**, **Gender**, **Education Level**, **Job Title**, and **Years of Experience**. The model is built using **Linear Regression**, and predictions can be made via a user-friendly **Streamlit app**.

### Key Features:
- Predict salaries based on various input features like **age**, **gender**, **education**, and **job title**.
- The pre-trained model, based on **scikit-learn**, is used for making predictions.
- The app allows users to input their details and receive a predicted salary.

## Files Included
1. **New_salary_app.ipynb**: Jupyter notebook containing the implementation of the salary prediction model, data exploration, and pre-processing steps.
2. **Salary_data.csv**: The dataset used for training the model, containing columns such as **Age**, **Gender**, **Education Level**, **Job Title**, **Years of Experience**, and **Salary**.
3. **salary_model.pkl**: A serialized pre-trained **Linear Regression** model used for salary predictions.
4. **salary_py.py**: A Python script for deploying the salary prediction model using **Streamlit**. This script serves as the backend of the web app.
5. **requirements.txt**: List of Python dependencies required for the project (e.g., **Streamlit**, **scikit-learn**, **numpy**, **joblib**).
