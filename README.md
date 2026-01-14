# Network Intrusion Detection System (NIDS)

A machine learning–based Network Intrusion Detection System that classifies network traffic as **NORMAL** or **ATTACK**.

## Dataset
- NSL-KDD dataset (improved version of KDDCup99)
- Loaded directly from public GitHub sources

## Tech Stack
- Python
- Pandas
- Scikit-learn

## Steps
1. Load NSL-KDD train and test datasets
2. Convert attack labels to binary classification
3. Preprocess data:
   - Standardize numeric features
   - One-hot encode categorical features
4. Train ML models:
   - Logistic Regression
   - Random Forest
5. Evaluate using accuracy, confusion matrix, and classification report
6. Predict intrusion on sample traffic

## How to Run
Open the notebook in Google Colab and run cells sequentially.

## Output
- Binary intrusion detection classifier
- Evaluation metrics
- Sample prediction (NORMAL / ATTACK)
