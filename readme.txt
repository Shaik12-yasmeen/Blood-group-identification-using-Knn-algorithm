Blood Group Identification Using KNN Algorithm

Overview
This project implements a K-Nearest Neighbors (KNN) algorithm to classify blood groups based on medical input features such as hemoglobin levels, RBC count, WBC count, platelets, etc.

Features
- Data preprocessing and normalization
- KNN model training and evaluation
- Accuracy score and confusion matrix
- User input-based blood group prediction

Algorithm
KNN is a supervised machine learning algorithm that classifies a new data point based on its nearest neighbors.

Steps:
1. Load and preprocess dataset
2. Normalize input features
3. Split dataset into train and test sets
4. Train KNN classifier
5. Predict blood group and evaluate model

Dataset
You may use a dataset with medical parameters such as:
- Hemoglobin
- RBC count
- WBC count
- Platelet count
- Age
- Gender
- Blood Group (Target)

Output
The model predicts blood group types:
A+, A-, B+, B-, AB+, AB-, O+, O-

Requirements
Python 3.8+
numpy
pandas
scikit-learn
matplotlib

How to Run
python blood_group_knn.py

Contact
For queries or improvements, feel free to reach out.
