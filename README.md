# CREDIT_CARD_FRAUD_DETECTION


## Overview

This project uses Machine Learning techniques to detect fraudulent credit card transactions. The goal is to build a classification model that can accurately distinguish between legitimate and fraudulent transactions, helping reduce financial losses and improve transaction security.

## Problem Statement

Credit card fraud is a significant issue in the financial industry. Fraudulent transactions represent only a small fraction of all transactions, making the dataset highly imbalanced. This project focuses on identifying fraudulent activities while minimizing false positives.

## Dataset

The dataset contains credit card transactions labeled as:

- Class 0: Legitimate Transaction
- Class 1: Fraudulent Transaction

### Features

The dataset includes:

- Time
- Amount
- Principal Components (V1 to V28)
- Class (Target Variable)

> Note: Most features are anonymized using PCA transformation for privacy reasons.

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Handling Class Imbalance
5. Feature Selection
6. Model Training
7. Model Evaluation
8. Fraud Prediction

## Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Machine Learning Models

Examples of models that can be used:

- Logistic Regression
- Random Forest Classifier
- Decision Tree Classifier
- XGBoost (Optional)

## Evaluation Metrics

Since the dataset is imbalanced, evaluation is based on:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

## Results

The trained model successfully identifies fraudulent transactions with high accuracy and strong recall performance. The final model can be used to predict whether a transaction is legitimate or fraudulent based on transaction features.

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
```

Install required packages:

```bash
pip install -r requirements.txt
```

## Usage

Run the notebook:

```bash
jupyter notebook
```

or open the project in Google Colab and execute all cells.

## Project Structure

```text
credit-card-fraud-detection/
│
├── Credit_Card_Fraud_Detection.ipynb
├── README.md
├── requirements.txt
└── dataset.csv
```

## Future Improvements

- Hyperparameter tuning
- Deep Learning approaches
- Real-time fraud detection system
- Deployment using Flask/FastAPI
- Interactive dashboard for monitoring transactions

## Author

Isha Negi

## License

This project is licensed under the MIT License.
