# System Threat Predictor – ML Analysis

A machine learning project built to predict the risk of malware infection in systems using data from antivirus software. Developed as part of a private IIT Madras BS Program Project.

## Problem Overview
The goal was to classify whether a system is likely to be infected by malware based on 75+ features. Each entry in the dataset represents a machine with various software, hardware, and behavioral attributes. The target variable indicates whether a threat was detected.

## What I Did
- Preprocessed a structured dataset with 100K+ rows and 75+ features
- Trained and evaluated three models
- Calculated accuracy, precision, recall, and ROC-AUC for performance comparison
- Identified system patterns most correlated with threat risk

## Tools Used
- Python
- pandas, numpy
- scikit-learn
- XGBoost, LightGBM
- matplotlib, seaborn

## Key Outcomes
- Built an end-to-end malware risk classification pipeline
- Gained hands-on experience in ML model evaluation and tuning
- Achieved 61% accuracy with the best-performing model
