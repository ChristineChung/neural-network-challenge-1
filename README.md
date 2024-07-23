# neural-network-challenge-1
Module 18 Challenge 

# Student Loan Risk with Deep Learning

## Description

This project aims to build a deep learning model to predict the risk of student loan repayment. The model is trained on a dataset containing various features related to student loans, such as academic data, financial data, loan details, demographics, and historical loan performance.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model](#model)
- [Evaluation](#evaluation)
- [Prediction](#prediction)
- [Recommendation System](#recommendation-system)

## Installation

1. Clone the repository
2. Install the required dependencies: `pandas`, `tensorflow`, `scikit-learn`

## Usage

1. Prepare the data by reading the `student-loans.csv` file and splitting it into features and target variables.
2. Split the data into training and testing sets.
3. Scale the features data using `StandardScaler`.
4. Create a deep neural network model using TensorFlow's Keras.
5. Compile and fit the model using the training data.
6. Evaluate the model using the testing data.
7. Save the model to a file (`student_loans.keras`).
8. Load the saved model and make predictions on the testing data.
9. Display the classification report.

## Data

The project uses the `student-loans.csv` dataset, which contains the following columns:

- Academic data (GPA, major, course load)
- Financial data (income, credit score, existing debts)
- Loan details (interest rates, terms, amounts)
- Demographics (age, location, family finances)
- Historical loan performance and default rates
- Credit ranking (target variable)

## Model

The project uses a deep neural network model with two hidden layers and a sigmoid output layer. The model is compiled with the binary cross-entropy loss function, the Adam optimizer, and the accuracy metric.

## Evaluation

The model's performance is evaluated using the testing data, and the loss and accuracy metrics are displayed.

## Prediction

The saved model is loaded, and predictions are made on the testing data. The predictions are saved to a DataFrame and rounded to binary results (0 or 1).

## Recommendation System

The README file also discusses the considerations for building a recommendation system for student loans, including:

1. Data needed (academic, financial, loan details, demographics, historical performance)
2. Filtering method (content-based filtering)
3. Real-world challenges (data privacy, bias, and fairness)
