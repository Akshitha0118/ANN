# Customer Churn Prediction using ANN & Streamlit

This project is a Customer Churn Prediction Web App built using Artificial Neural Networks (ANN) with TensorFlow/Keras and deployed using Streamlit.
The model predicts whether a bank customer is likely to churn (leave the bank) based on demographic and financial features.

## 🚀 Project Overview

Customer churn is a critical problem in the banking industry. Retaining existing customers is more cost-effective than acquiring new ones.
This application helps predict churn by learning patterns from historical customer data using a deep learning model.

## 🧠 Machine Learning Model

Model Type: Artificial Neural Network (ANN)

Framework: TensorFlow / Keras

Problem Type: Binary Classification

## Output:

1 → Churn

0 → No Churn

## ANN Architecture:

Input Layer

Hidden Layers:

Dense (6 units, ReLU)

Dense (6 units, ReLU)

Dense (5 units, ReLU)

Dense (4 units, ReLU)

## Output Layer:

Dense (1 unit, Sigmoid)

## 📊 Dataset

Dataset Name: Churn_Modelling.csv

Target Variable: Exited

Features Used:

Credit Score

Geography

Gender

Age

Tenure

Balance

Number of Products

Has Credit Card

Is Active Member

Estimated Salary

## ⚙️ Data Preprocessing

Label Encoding for Gender

One-Hot Encoding for Geography

Feature Scaling using StandardScaler

Train-Test Split: 80% / 20%

## 🖥️ Streamlit Web App Features

Interactive sidebar inputs for customer details

Real-time churn prediction

Displays:

Prediction result (Churn / No Churn)

Model accuracy

Confusion matrix

## 📦 Tech Stack

Python 🐍

Pandas & NumPy

Scikit-learn

TensorFlow / Keras

Streamlit
