# Loan Approval Prediction 

## Overview

This project is a **Machine Learning based Loan Approval Prediction System** that predicts whether a loan application is **Approved or Rejected** based on applicant financial details.
The model learns patterns from historical loan application data and provides predictions through a simple web interface.

The system is designed as a **demonstration of how banks and financial institutions can use machine learning to support loan decision making**.

---

## What the Project Predicts

The model predicts:

**Loan Status**

* Approved
* Rejected

The prediction is based on important financial inputs such as:

* Applicant Income
* Loan Amount
* Loan Duration (Years)

These factors help estimate the applicant’s **ability to repay the loan**.

---

## How the Prediction Works

The system follows a standard **machine learning pipeline**:

1. **Dataset Loading**

   * Loan dataset is loaded using Pandas.

2. **Data Preprocessing**

   * Column names cleaned
   * Missing values removed
   * Categorical variables encoded using LabelEncoder

3. **Feature Selection**

   * Important attributes like income and loan amount are used as model inputs.

4. **Model Training**

   * A **Random Forest Classifier** is trained on the dataset to learn relationships between applicant information and loan approval.

5. **Prediction**

   * User enters financial details in the web interface.
   * The trained model processes the inputs.
   * The model predicts whether the loan is likely to be approved or rejected.

---

## Technologies Used

**Programming Language**

* Python

**Libraries**

* Pandas (data handling)
* Scikit-learn (machine learning)
* Gradio (web interface)
* NumPy

**Machine Learning Algorithm**

* Random Forest Classifier

**Development Environment**

* Google Colab / Python Notebook

---

## Project Workflow

Dataset → Data Cleaning → Feature Encoding → Model Training → Model Evaluation → Web Interface → User Prediction

---

## Example Input

Applicant Income: 8000
Loan Amount: 300000
Loan Years: 2

Output:
Loan Approved

Applicant Income: 5000
Loan Amount: 300000
Loan Years: 1

Output:
Loan Rejected

---

## Purpose of the Project

The goal of this project is to demonstrate:

* Application of **machine learning in financial decision making**
* Building an **interactive ML web application**
* Understanding **credit risk prediction**

---

## Future Improvements

Possible improvements include:

* Adding credit score and employment history features
* Using advanced models like Gradient Boosting
* Deploying the model as a public web application
* Building a full banking dashboard

---

## Author
Ruchit Bhalekar
