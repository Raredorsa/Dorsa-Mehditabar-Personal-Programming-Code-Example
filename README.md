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
```

### Feature Scaling

Features are normalized using:

```python
MinMaxScaler()
```

---

## 3. Train-Test Split

The dataset is divided into training and testing sets using stratified sampling:

```python
train_test_split(..., stratify=y)
```

This preserves the class distribution across both sets.

---

## 4. Handling Imbalanced Data

The dataset contains imbalanced classes.

To address this issue, SMOTE (Synthetic Minority Oversampling Technique) is applied:

```python
SMOTE()
```

SMOTE generates synthetic samples for the minority class to improve model performance.

---

## 5. Model Training

The project uses:

```python
RandomForestClassifier()
```

Random Forest was selected because it performs well on structured tabular healthcare datasets and is robust against overfitting.

---

## 6. Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Example:

```python
classification_report()
confusion_matrix()
```

---

## 7. Data Visualization

Visualization is performed using matplotlib and seaborn to better understand:
- Class distribution
- Model performance
- Confusion matrix results

---

# Quantum Machine Learning Exploration

This project also explores Quantum Machine Learning using Qiskit.

Experimental components include:
- Quantum Support Vector Classifier (QSVC)
- Quantum Kernels
- Hybrid Classical-Quantum workflows

---

# Project Structure

```text
project/
│
├── data/
│   └── nhanes_merged.csv
│
├── notebooks/
│   └── diabetes_prediction.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── train.py
│   ├── evaluate.py
│
├── results/
│
├── requirements.txt
│
└── README.md
```

---

# Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repository-name.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# Running the Project

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Or run the Python script:

```bash
python main.py
```

---

# Future Improvements

Potential future improvements include:

- Hyperparameter tuning
- Cross-validation
- ROC-AUC optimization
- Feature importance analysis
- Explainable AI (SHAP/LIME)
- Full Quantum ML implementation
- Comparison with additional ML models

---

# Learning Outcomes

Through this project, I gained practical experience in:

- End-to-end machine learning workflows
- Healthcare data preprocessing
- Imbalanced dataset handling
- Model evaluation techniques
- Data visualization
- Introduction to Quantum Machine Learning

---

# License

This project is open-source and available under the MIT License.
