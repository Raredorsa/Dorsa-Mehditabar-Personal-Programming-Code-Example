# Dorsa-Mehditabar-Personal-Programming-Code-Example
# Diabetes Prediction using Machine Learning and Quantum Computing

A machine learning project focused on predicting diabetes using healthcare data from the NHANES dataset.

This project includes:
- Data preprocessing
- Missing value handling
- Imbalanced dataset treatment using SMOTE
- Model training and evaluation
- Data visualization
- Initial exploration of Quantum Machine Learning using Qiskit

---

# Project Overview

The main goal of this project is to build a reliable diabetes prediction model using healthcare-related features.

The workflow includes:
- Data cleaning and preprocessing
- Feature scaling
- Handling imbalanced data
- Training machine learning models
- Evaluating model performance
- Exploring Quantum Machine Learning approaches

---

# Dataset

The dataset contains healthcare-related information such as:

- Age
- BMI
- Blood Pressure
- Dietary Information
- Alcohol Consumption
- Other medical indicators

Target Variable:
- `Diabetes`

This is a binary classification problem.

---

# Technologies Used

## Programming Language
- Python

## Libraries
- pandas
- numpy
- scikit-learn
- imbalanced-learn
- matplotlib
- seaborn
- qiskit
- qiskit-machine-learning

---

# Machine Learning Pipeline

## 1. Data Loading

The dataset is loaded using pandas and inspected to understand:
- Data structure
- Feature types
- Missing values

---

## 2. Data Preprocessing

### Missing Value Handling
Missing numerical values are handled using:

```python
SimpleImputer(strategy='mean')
