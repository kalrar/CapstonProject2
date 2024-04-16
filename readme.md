# Anomaly Detection Project

## Overview

This project aims to develop a robust anomaly detection pipeline using various machine learning techniques. The pipeline encompasses data preprocessing, exploratory data analysis, outlier detection, feature selection, hyperparameter tuning, and model evaluation. The ultimate goal is to identify and mitigate anomalies within the dataset, enabling stakeholders to make informed decisions and mitigate risks effectively.

## Dataset

The dataset used in this project is sourced from AnomaData.xlsx, containing a time-series of multivariate data. It comprises features such as 'x1', 'x2', ..., 'x60', along with a binary target variable 'y' indicating anomalies (1) and normal instances (0).

## Pipeline Components

1. **Data Preprocessing**: 
   - Handling missing values
   - Data standardization
   - Feature engineering (e.g., extracting time-related features)

2. **Exploratory Data Analysis (EDA)**:
   - Visualizing distributions of features
   - Exploring correlations between features
   - Identifying trends and patterns in the data

3. **Outlier Detection**:
   - Utilizing Isolation Forest, One-Class SVM, and Local Outlier Factor algorithms
   - Removing outliers from numerical features
   - Balancing outlier elimination with preserving minority classes

4. **Feature Selection**:
   - Selecting top features using univariate feature selection (SelectKBest)
   - Considering features with high predictive power for anomaly detection

5. **Hyperparameter Tuning**:
   - Grid search with cross-validation to optimize model parameters
   - Tuning parameters for Isolation Forest, One-Class SVM, and Local Outlier Factor

6. **Model Evaluation**:
   - Assessing model performance using metrics such as precision, recall, and F1-score
   - Iteratively refining models to enhance anomaly detection efficacy

## Results

The project yields insights into the effectiveness of various anomaly detection models, with a notable emphasis on precision improvement through hyperparameter tuning and model refinement. The README provides a comprehensive overview of the methodologies employed, key findings, and implications for stakeholders.

## Usage

1. **Dependencies**:
   - Python 3.x
   - Required libraries: pandas, matplotlib, seaborn, scikit-learn

2. **Instructions**:
   - Clone the repository to your local machine
   - Ensure the dataset (AnomaData.xlsx) is located in the appropriate directory
   - Run the provided Python scripts in a Jupyter Notebook or any Python IDE