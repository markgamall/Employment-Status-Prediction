# Employment Status Prediction

## Overview
This project predicts teacher employment outcomes (placed/not placed/absent) using academic qualifications, exam performance metrics, and administrative records. The dataset contains comprehensive information from multiple educational districts, including test scores, interview evaluations, and professional background details.

## Key Features
- Data Preprocessing: Handled outliers, performed feature transformations (log scaling), and encoded categorical variables
- Feature Engineering: Created new features
- Imbalanced Data Handling: Tested SMOTE, ADASYN, Random Oversampling, and NearMiss techniques
- Model Evaluation: Compared 9 different models with hyperparameter tuning

## Best Model: 
Random Forest with Random Oversampling achieved 99.7% accuracy.
