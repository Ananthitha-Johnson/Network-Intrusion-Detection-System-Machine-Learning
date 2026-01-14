# Network Intrusion Detection System using Machine Learning

This project implements a machine learning–based Network Intrusion Detection System (NIDS) to identify malicious network traffic and classify connections as **Normal** or **Attack**.

---

## Problem Statement
Modern networks face increasing cyber threats such as denial-of-service and unauthorized access attacks.  
This project aims to automatically detect network intrusions using supervised machine learning models.

---

## Dataset
- NSL-KDD Dataset
- Improved version of the KDDCup99 dataset
- Contains network traffic features and attack labels

Target Variable:
- Normal vs Attack traffic

---

## Methodology
1. Load and preprocess NSL-KDD dataset
2. Encode categorical features
3. Normalize numerical features
4. Train classification models:
   - Logistic Regression
   - Random Forest
5. Evaluate using standard classification metrics

---

## Results
- The trained model effectively distinguishes malicious traffic from normal traffic.
- Evaluation metrics include:
  - Accuracy
  - Confusion Matrix
  - Classification Report

---

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Network Security Dataset (NSL-KDD)

---

## How to Run
1. Open the notebook in Google Colab
2. Run all cells sequentially
3. View predictions and evaluation metrics

---

## Output
<img width="789" height="464" alt="Network_Intrusion_Output" src="https://github.com/user-attachments/assets/97fa6a82-5d3f-496e-81de-e7037b6925ac" />

---

## Key Learning Outcomes
- Understanding network intrusion detection concepts
- Feature engineering on security datasets
- Application of ML in cybersecurity

---

## Future Improvements
- Multi-class attack classification
- Real-time intrusion detection
- Deep learning–based anomaly detection

---

## Author
**Ananthitha Johnson**  
BSc (Hons) in Computer Science
