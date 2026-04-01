# Malicious URL Detection using Machine Learning

MLCS Lab Experiment 7 | K.J. Somaiya College of Engineering | 2025-26

## Overview
A machine learning system that classifies URLs as **Safe** or **Malicious** by extracting structural features from URL strings and training classification models.

## Features Extracted
- URL length, hostname length, path length
- Character counts (dots, hyphens, slashes, digits, special characters)
- Boolean flags (HTTPS, @ symbol, double slashes, port presence)
- URL Shannon entropy
- Subdomain count

## Models Used
- Logistic Regression
- Random Forest
- Gradient Boosting

## Dataset
Labeled dataset of benign and malicious URLs with structural feature extraction applied during preprocessing.

## How to Run
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook
```
Open the notebook and run all cells. The model will train and predict on sample URLs at the end.

## Sample Prediction
```
[SAFE]       https://www.google.com/search?q=python
[MALICIOUS]  http://free-iphone-winner.xyz/claim@now//download
[SAFE]       https://github.com/user/repository
[MALICIOUS]  http://192.168.0.1:8080/admin/shell.php
```

## Tech Stack
Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
