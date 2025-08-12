# NTI First Task: Customer Churn Prediction with ANN

# Project Overview
This repository contains a Jupyter Notebook implementing an Artificial Neural Network (ANN) to predict customer churn based on the "Churn_Modelling.csv" dataset. The model is built using TensorFlow/Keras and includes data preprocessing, model training, and evaluation steps. The goal is to predict whether a bank customer will leave (churn) based on features like credit score, geography, gender, age, and more.
Repository Contents

# Artificial Neural Networks (ANN).ipynb: The main Jupyter Notebook with the ANN implementation.
# Churn_Modelling.csv: The dataset used for training and testing the model.
# .gitignore: Ignores unnecessary files like Jupyter checkpoints and Python cache files.

# Dataset
The dataset (Churn_Modelling.csv) contains 10,000 rows of customer data 

# Model Architecture:

The ANN has three layers:
Two hidden layers with 6 neurons each (ReLU activation).
One output layer with 1 neuron (sigmoid activation for binary classification).

Compiled with the Adam optimizer and binary cross-entropy loss.


# Training:

The model is trained for 100 epochs with a batch size of 32.
Training accuracy improves to ~86% by the final epoch.


This project is licensed under the MIT License.
For questions, reach out via GitHub issues or contact Abdalah Mohamed.