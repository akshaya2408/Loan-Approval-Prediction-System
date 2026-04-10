# Loan Approval Prediction System

A machine learning web application that predicts whether a loan application is likely to be approved based on applicant details such as income, education, employment status, loan amount, credit history, and other relevant features.

## Overview

The main goal of this project is to automate the loan approval prediction process using machine learning. It helps reduce manual effort and provides quick predictions based on historical applicant data.

This project covers the complete ML pipeline:
- Data preprocessing
- Handling missing values
- Encoding categorical features
- Model training and evaluation
- Prediction through a Flask web application

## Features

- Predicts loan approval status from user input
- Performs data cleaning and preprocessing
- Uses machine learning classification algorithms
- Compares model performance
- Simple web interface for real-time prediction
- Easy to deploy and use

## Tech Stack

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn
- **Backend:** Flask
- **Frontend:** HTML, CSS
- **Model Serialization:** Pickle / Joblib

## Problem Statement

Loan approval is an important decision-making process in the banking and finance sector. Manual evaluation of loan applications can be time-consuming and may lead to inconsistencies. This project uses machine learning to predict whether a loan should be approved based on applicant information.

## Dataset Features

The model is trained on features commonly used in loan approval analysis, such as:

- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area

**Target Variable:**
- `Loan_Status`

## Project Workflow

### 1. Data Collection
The dataset is loaded from a CSV file containing historical loan application records.

### 2. Data Preprocessing
- Checked for missing values
- Filled null values using suitable strategies
- Converted categorical values into numerical format
- Selected important input features

### 3. Exploratory Data Analysis
- Understood the distribution of applicant features
- Observed relationships between credit history, income, and loan approval
- Identified important factors affecting predictions

### 4. Model Building
Different classification models can be trained, such as:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### 5. Model Evaluation
The models are evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report

### 6. Deployment
The best-performing model is saved and integrated into a Flask web application where users can enter their details and receive a prediction.

## Project Structure

```bash
Loan-Approval-Prediction-System/
│
├── static/                 # CSS files
├── templates/              # HTML templates
├── model/                  # Saved ML model files
├── app.py                  # Flask application
├── train_model.py          # Model training script
├── loan_data.csv           # Dataset
├── requirements.txt        # Required Python packages
├── README.md               # Project documentation
└── .gitignore
