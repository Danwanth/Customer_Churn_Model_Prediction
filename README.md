# Customer Churn Model Prediction

A machine learning project focused on predicting customer churn using classification algorithms and ensemble learning techniques. The project analyzes customer banking data to determine whether a customer is likely to leave the service.

## Project Overview

This project uses customer information such as:

* Credit Score
* Geography
* Gender
* Age
* Balance
* Tenure
* Number of Products
* Estimated Salary

to predict customer churn (`Exited` column).

The notebook covers the complete machine learning pipeline including preprocessing, feature engineering, dimensionality reduction, classification, regression, and ensemble methods.

## Features

* 📊 Exploratory Data Analysis
* 🧹 Data preprocessing and cleaning
* 📉 Outlier removal using IQR
* 🔤 Label Encoding & One-Hot Encoding
* ⚖️ Feature scaling using StandardScaler
* 🎯 Feature selection using SelectKBest
* 📦 PCA dimensionality reduction
* 🤖 Multiple ML classification models
* 🧠 Ensemble learning with VotingClassifier
* 📈 Model evaluation and visualization

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Machine Learning Workflow

### 1. Data Preprocessing

The project performs:

* Null value checking
* Removal of unnecessary columns
* Outlier detection using IQR
* Encoding categorical variables
* Feature scaling

## Classification Models Used

### Logistic Regression

Used as a baseline classification model.

### Decision Tree Classifier

Captures nonlinear relationships in the dataset.

### Random Forest Classifier

Improves prediction performance using ensemble trees.

## Ensemble Learning

The project also implements:

* Hard Voting Classifier
* Soft Voting Classifier

to combine predictions from multiple models for better performance.

## Feature Engineering Techniques

### Feature Selection

Uses:

```python id="iz9kl9"
SelectKBest(score_func=chi2, k=8)
```

to select the most important features.

### PCA (Principal Component Analysis)

Used for dimensionality reduction and variance retention.

## Regression Models Included

Apart from churn prediction, the notebook also experiments with predicting `EstimatedSalary` using:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

## Evaluation Metrics

### Classification Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix

### Regression Metrics

* MAE
* MSE
* RMSE
* R² Score

## Installation

Clone the repository:

```bash id="wz76mu"
git clone https://github.com/Danwanth/Customer_Churn_Model_Prediction.git
```

Move into the project directory:

```bash id="nb10n2"
cd Customer_Churn_Model_Prediction
```

Install dependencies:

```bash id="dl8f2j"
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash id="vh5mj2"
jupyter notebook
```

## Project Structure

```text id="c2v32e"
Customer_Churn_Model_Prediction/
│
├── Customer_Churn.ipynb
├── Churn_Modelling.csv
├── README.md
└── requirements.txt
```

## Future Improvements

* Hyperparameter tuning
* XGBoost integration
* Streamlit deployment
* Cross-validation
* SHAP explainability
* Handling class imbalance

## Learning Outcomes

This project demonstrates:

* Data preprocessing techniques
* Classification and regression workflows
* Ensemble learning concepts
* Feature engineering
* Model evaluation and comparison

## Repository

[Customer Churn Model Prediction Repository](https://github.com/Danwanth/Customer_Churn_Model_Prediction?utm_source=chatgpt.com)
