# Loan Approval Prediction System

A Machine Learning project that predicts whether a loan application is likely to be approved based on applicant information such as income, loan amount, credit history, marital status, and other financial attributes.

## Project Overview

Financial institutions receive a large number of loan applications every day. Evaluating each application manually can be time-consuming and prone to inconsistencies. This project uses Machine Learning techniques to automate the loan approval prediction process and assist in decision-making.

The system analyzes applicant data, performs preprocessing and feature engineering, and compares multiple classification algorithms to determine the most effective model for loan approval prediction.

## Features

* Data preprocessing and cleaning
* Missing value handling
* Feature engineering
* Exploratory Data Analysis (EDA)
* Data visualization using Matplotlib and Seaborn
* Multiple Machine Learning models
* Model performance comparison
* Classification report generation

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Dataset Features

The model uses the following attributes:

* Gender
* Married
* Dependents
* Education
* Self Employed
* Applicant Income
* Coapplicant Income
* Loan Amount
* Loan Amount Term
* Credit History
* Property Area
* Loan Status (Target Variable)

## Data Preprocessing

The following preprocessing steps were performed:

* Handling missing values
* Log transformation for skewed features
* Feature engineering using Total Income
* Label Encoding for categorical variables
* Feature Scaling using StandardScaler

## Machine Learning Models Implemented

### Random Forest Classifier

* Ensemble learning algorithm
* Handles complex patterns effectively
* Achieved strong prediction performance

### Gaussian Naive Bayes

* Probabilistic classification model
* Fast and efficient for structured datasets

### Decision Tree Classifier

* Tree-based learning algorithm
* Easy to interpret and visualize

### K-Nearest Neighbors (KNN)

* Instance-based learning approach
* Classifies samples using nearest neighbors

## Model Evaluation

The models were evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Classification Report

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Handle Missing Values
5. Feature Engineering
6. Exploratory Data Analysis
7. Encode Categorical Variables
8. Scale Features
9. Train-Test Split
10. Model Training
11. Prediction
12. Performance Evaluation

## Repository Structure

```text
Loan-Approval-Prediction-System/
│
├── loan_approval.ipynb
├── Dataset.csv
├── README.md
└── requirements.txt
```

## Installation

Clone the repository:

```bash
git clone https://github.com/akshaya2408/Loan-Approval-Prediction-System.git
```

Navigate to the project directory:

```bash
cd Loan-Approval-Prediction-System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Run the Project

Open the notebook:

```bash
jupyter notebook
```

Then run:

```text
loan_approval.ipynb
```

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* Logistic Regression implementation
* Support Vector Machine (SVM) model
* Model deployment using Flask or Streamlit
* Real-time loan approval prediction interface

## Learning Outcomes

Through this project, I gained practical experience in:

* Data preprocessing
* Feature engineering
* Exploratory Data Analysis
* Classification algorithms
* Model evaluation techniques
* Machine Learning workflow implementation


⭐ If you found this project useful, consider giving it a star.
