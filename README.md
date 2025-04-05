# Human-Activity-Recognition
Developed a Human Activity Recognition system using the UCI HAR dataset, analyzing 7352 training and 2947 test samples with 561 features, achieving up to 96.64% accuracy with Linear SVC. Implemented an LSTM model, achieving 92.43% accuracy on time series data.


This project involves developing and evaluating machine learning models for classifying human activities from sensor data. The dataset used is the UCI Human Activity Recognition (HAR) dataset, which includes data from accelerometers and gyroscopes.

Dataset Overview

Training Samples: 7352

Test Samples: 2947

Features: 561

Project Objectives

Exploratory Data Analysis (EDA): Conducted EDA to understand the structure of the data, including visualization of stationary and moving activities.

Model Development: Implemented and compared the performance of several machine learning models:

Logistic Regression

Linear SVC

Kernel SVM (RBF)

Decision Tree

Random Forest

LSTM Model: Developed an LSTM model for time series classification to leverage temporal dependencies in activity recognition.

Key Findings

Best Performing Model: Linear SVC achieved the highest accuracy of 96.64%.

LSTM Performance: The LSTM model achieved a test accuracy of 92.43%, demonstrating its effectiveness in handling time series data.

Data Insights: EDA and t-SNE visualizations provided valuable insights into data structure and activity clustering.

Code Structure

Data Preprocessing: Scripts for loading and preprocessing the UCI HAR dataset.

Model Implementations: Code for each machine learning model, including hyperparameter tuning using Grid Search.

Evaluation Metrics: Functions for calculating accuracy, confusion matrices, and classification reports.
