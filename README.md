# PCA Cancer Data Analysis

## Overview
This project performs Principal Component Analysis (PCA) on the breast cancer dataset from `sklearn.datasets`. The PCA reduces the dataset to two principal components, which are then visualized. A logistic regression model is optionally implemented for classification.

## Files
- `pca_analysis.py`: Main Python script for PCA and logistic regression.
- `Figure_1_Scatterplot.png`: Visualization of PCA components.
- `classification_report.txt`: Logistic regression evaluation report.
- `README.md`: Project documentation.

## Data Preparation
- The breast cancer dataset was loaded and standardized using `StandardScaler`.
- PCA was applied to reduce the dataset to 2 components.

## How to Run
1. Open the terminal in the project directory.
2. Run the script:
   ```bash
   python pca_analysis.py
