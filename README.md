# Credit Card Fraud Detection 

This project aims to detect fraudulent credit card transactions using machine learning techniques. 
The dataset used is highly imbalanced, making this a real-world scenario where fraud cases are rare compared to normal transactions.

## Project Structure

- `credit-card-fraud-detection.ipynb`: Jupyter Notebook with the full data preprocessing, exploration, modeling, and evaluation pipeline.
- `README.md`: Project overview and documentation.

## Dataset

- **Source**: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Features**:
  - 284,807 transactions
  - 492 frauds (Class 1)
  - 30 features: `V1`–`V28` (PCA-transformed), `Time`, `Amount`, and `Class` (target)

## Techniques Used

- Data Preprocessing:
  - Handling class imbalance using undersampling/oversampling
  - Feature scaling using StandardScaler
  - Train-test splitting

- Modeling:
  - Logistic Regression

- Evaluation Metrics:
  - Accuracy

