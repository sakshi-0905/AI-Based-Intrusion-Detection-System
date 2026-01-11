# AI-Based Intrusion Detection System using Machine Learning

## Overview
This project presents an AI-based Intrusion Detection System (IDS) developed using machine learning techniques to classify network traffic as normal or malicious. The system is designed to improve detection accuracy and reduce false positives in network security environments.

## Objective
To build an intelligent intrusion detection model capable of identifying cyber-attacks using supervised machine learning.

## Dataset
- **NSL-KDD Dataset**
- File used: `KDDTrain+.txt`
- Labels converted into:
  - `0` → Normal
  - `1` → Attack

## Methodology
1. Data preprocessing and labeling
2. One-hot encoding of categorical features
3. Feature scaling using StandardScaler
4. Model training using Random Forest Classifier
5. Performance evaluation using accuracy, recall, ROC-AUC, and confusion matrix

## Machine Learning Model
- Algorithm: Random Forest Classifier
- Estimators: 150
- Max Depth: 20
- Class Weight: Balanced

## Evaluation Metrics
- Accuracy
- Recall
- ROC-AUC Score
- Confusion Matrix

## Results
The trained model demonstrates strong detection capability with high recall, making it suitable for intrusion detection scenarios where minimizing false negatives is critical.

## How to Run the Project
```bash
pip install -r requirements.txt
cd src
python AI_IDS_Model.ipynb
