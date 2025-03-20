# Fraud-Detection-System

Fraud Detection System

Description

This project implements a fraud detection system using a dataset like the Credit Card Fraud Dataset. It trains a machine learning model to classify transactions as fraudulent or legitimate. The system includes:

Data Preprocessing: Handling missing values, standardizing features, and addressing class imbalance using SMOTE.

Model Training: Training a Random Forest Classifier.

Model Evaluation: Computing precision, recall, F1-score, and confusion matrix.

Testing Interface: A command-line interface (CLI) for manual transaction input and an automated test case.

Technologies Used

Python

Pandas & NumPy

Scikit-learn

Imbalanced-learn (SMOTE)

Joblib

Installation

Clone the repository:

Install dependencies:

Run the script in Google Colab (if needed, upload the dataset manually).

Usage

Upload the dataset manually when prompted in Google Colab.

The script will:

Train a fraud detection model.

Print evaluation metrics.

Run an automated test case.

You can manually test transactions by entering feature values.

Model Evaluation

The model performance is assessed using:

Confusion Matrix

Precision, Recall, and F1-score

Example Test Transaction

When prompted, enter 30 feature values like:

Output:

or

License

This project is open-source. Feel free to modify and improve it!

