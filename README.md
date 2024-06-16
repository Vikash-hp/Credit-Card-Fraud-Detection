# Credit Card Fraud Detection


## Overview
Credit card fraud detection is crucial for financial institutions to protect customers from unauthorized transactions and to minimize financial losses. This project uses historical transaction data to train a machine learning model capable of predicting fraudulent transactions.

## Dataset
The dataset used in this project is the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle. It contains transactions made by European cardholders in September 2013, with 284,807 transactions and 31 features.

### Features
- `Time`: Number of seconds elapsed between this transaction and the first transaction in the dataset.
- `V1` to `V28`: Result of a PCA transformation to protect user identities and sensitive features.
- `Amount`: Transaction amount.
- `Class`: Target variable (1 for fraud, 0 for non-fraud).

## Installation
To run this project, you need to have Python installed along with the following packages:
- pandas
- numpy
- scikit-learn

  
# You can install the required packages using:
```bash```
pip install -r requirements.txt

# Evaluation Metrics
- Accuracy:98.07%

# Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements, bug fixes, or suggestions.
