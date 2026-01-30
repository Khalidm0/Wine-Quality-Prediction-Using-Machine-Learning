# Wine Quality Prediction Using Machine Learning

## Overview
This project presents a comparative study of multiple supervised machine learning algorithms for binary wine quality prediction. The goal is to replace subjective human sensory evaluation with an objective, scalable, and data-driven approach using physicochemical properties of wine.

The system predicts whether a wine sample is of good or bad quality based on measurable chemical attributes such as alcohol content, acidity, sulphates, pH, density, and sulfur dioxide levels.

## Objectives
- Predict wine quality using binary classification (good / bad)
- Compare performance of multiple supervised ML classifiers
- Analyze the impact of physicochemical features on wine quality
- Provide a scalable and cost-effective alternative to manual evaluation

## Datasets
- Wine Type Classification Dataset (red & white wines)
- Processed Wine Quality Dataset (binary labels)

## Data Preprocessing
- Duplicate removal
- Outlier handling
- Feature scaling (Standardization)
- Label transformation (quality → binary)
- Train–test split (80% / 20%)

## Machine Learning Models
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- CatBoost
- Neural Network (MLP)

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- ROC–AUC

## Results
Experimental results show that ensemble models, especially Random Forest and Neural Networks, achieve the highest performance, while simpler models provide competitive baseline accuracy with lower computational cost.

## Technologies Used
- Python
- NumPy, Pandas
- Scikit-learn
- CatBoost
- Matplotlib / Seaborn
- Jupyter Notebook

## Project Status
Completed, evaluated, and ready for academic submission.
