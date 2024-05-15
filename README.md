# Loan Prediction

This project aims to predict loan approval status using machine learning models. The main goal is to help financial institutions automate the loan approval process and improve efficiency.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required packages.

```bash
pip install -r requirements.txt
```
## Usage
To run the project, use the following command:

```bash
mlflow run git@github.com:NishchalRavish/Loan_Prediction.git --experiment-name Loan_prediction
```
## Data
The dataset used for this project is available in the data directory. It contains information about loan applicants such as their income, credit history, loan amount, etc.

## Models
Several machine learning models are implemented in this project, including:

Logistic Regression

Random Forest

Gradient Boosting

## Evaluation
The models are evaluated based on accuracy, precision, recall, and F1-score. The best-performing model is selected for predicting loan approval status.
