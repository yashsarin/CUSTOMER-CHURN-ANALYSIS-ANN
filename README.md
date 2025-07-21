# CUSTOMER-CHURN-ANALYSIS-ANN
# 📉 Customer Churn Prediction Using MLPClassifier

This project focuses on predicting customer churn in the telecom industry using a Multi-Layer Perceptron (MLP) neural network from Scikit-learn. Churn prediction helps businesses identify unhappy customers early and take proactive steps to retain them.

---

## 🔍 Problem Statement

Customer churn refers to when clients stop doing business with a company. The goal of this project is to build a reliable machine learning model that predicts whether a customer is likely to churn based on their demographics and service usage patterns.

---

## 📂 Dataset

- **Filename**: `customer_churn.csv`
- **Source**: Telecom domain
- **Features**:
  - Demographics: Gender, SeniorCitizen, Partner, Dependents
  - Services: InternetService, OnlineSecurity, TechSupport, etc.
  - Account Info: Tenure, Contract, MonthlyCharges, TotalCharges
  - **Target**: `Churn` (Yes/No)

---

## 🧪 Technologies Used

- **Python**
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Visualization
- **Scikit-learn** – Preprocessing, model building, evaluation

---

## 🧹 Data Preprocessing

- Removed `customerID` column
- Converted `TotalCharges` to numeric type
- Handled missing or blank values
- Encoded categorical features using label and one-hot encoding
- Normalized numerical features

---

## 🤖 Model: Multi-Layer Perceptron (MLPClassifier)

- **Library**: `sklearn.neural_network.MLPClassifier`
- **Architecture**:
  - Input layer: Features
  - Hidden layers: Configurable (default: one hidden layer)
  - Output layer: Binary output (Churn or Not)
- **Activation Function**: ReLU
- **Optimizer**: Adam
- **Loss Function**: Log-loss (for classification)
- **Training Iterations**: Adjusted via `max_iter`

---

## 📊 Model Evaluation

- **Train/Test Split**
- **Confusion Matrix**
- **Accuracy, Precision, Recall, F1-Score**
- **Classification Report**
- **Loss Curve Visualization (if enabled)**

---

## 📈 Results

The `MLPClassifier` achieved reliable accuracy in predicting churn. Proper preprocessing and tuning helped improve generalization on the test set.

---

## 🚀 How to Run

1. Clone this repository.
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib scikit-learn

