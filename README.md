# Dorsa-Mehditabar-Personal-Programming-Code-Example
Diabetes Prediction using Machine Learning and Quantum Computing

A machine learning project focused on predicting diabetes using healthcare data from the NHANES dataset.
This project includes data preprocessing, imbalance handling with SMOTE, classical machine learning models, performance evaluation, and initial experimentation with Quantum Machine Learning using Qiskit.

Project Overview

The goal of this project is to build a reliable diabetes prediction system using patient healthcare data.
The workflow includes:

Data cleaning and preprocessing
Missing value handling
Feature scaling
Imbalanced dataset treatment
Model training and evaluation
Visualization of results
Exploration of Quantum Machine Learning techniques
Dataset

The project uses healthcare-related data containing features such as:

Age
BMI
Blood Pressure
Dietary Information
Alcohol Consumption
Other medical indicators

Target variable:

Diabetes (Binary Classification)
Technologies Used
Programming Language
Python
Libraries
Pandas
NumPy
Scikit-learn
Imbalanced-learn (SMOTE)
Matplotlib
Seaborn
Qiskit
Qiskit Machine Learning
Machine Learning Pipeline
1. Data Loading

The dataset is loaded using Pandas and inspected for structure, missing values, and feature types.

2. Data Preprocessing
Missing values handled using SimpleImputer
Feature normalization using MinMaxScaler
3. Train-Test Split

The dataset is divided into training and testing sets using stratified sampling to preserve class distribution.

4. Handling Imbalanced Data

SMOTE (Synthetic Minority Oversampling Technique) is used to balance diabetic and non-diabetic classes.

5. Model Training

A RandomForestClassifier is trained on the processed dataset.

6. Model Evaluation

Evaluation metrics include:

Accuracy
Precision
Recall
F1-score
Confusion Matrix
7. Visualization

Model performance and classification results are visualized using Seaborn and Matplotlib.

Quantum Machine Learning Exploration

This project also explores the integration of Quantum Machine Learning using Qiskit.

Planned/experimental components include:

Quantum Support Vector Classifier (QSVC)
Quantum Kernels
Hybrid Classical-Quantum Workflows
