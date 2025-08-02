# Network Intrusion Detection System (NIDS) using Random Forest
This project presents a Machine Learning-based Network Intrusion Detection System (NIDS) using a labeled dataset to identify malicious network activity. Built and tested in IBM Watson Studio, the system classifies traffic as either normal or anomalous using a Random Forest classifier.

 1.Features
Uses KDD-based dataset with 42 network traffic features.

Applies feature encoding, train-test split, and model training using Scikit-learn.

Evaluates using accuracy, precision, recall, and confusion matrix.

Built-in support for handling unseen categories in test data.

2. ML Model
Algorithm: Random Forest

Libraries: pandas, scikit-learn, seaborn, matplotlib

3. Use Case
This project is a cybersecurity-focused application that demonstrates how machine learning models can assist in:

Detecting abnormal network patterns

Preventing unauthorized access or intrusions

Enhancing proactive defense mechanisms in network infrastructures

4. Files
NIDS_Model.ipynb: Complete Jupyter notebook with data loading, preprocessing, model training, and evaluation.

Train_data.csv & Test_data.csv: Used in IBM Cloud Object Storage.
