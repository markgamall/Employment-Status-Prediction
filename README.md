# Employment Status Prediction

## Overview
This project predicts employment status (placed/not placed/absent) based on academic qualifications, exam scores, and other relevant features. The dataset includes records from various administrative units with imbalanced classes, which was addressed using oversampling techniques.

## Key Features
- Data Preprocessing: Handled outliers, performed feature transformations (log scaling), and encoded categorical variables
- Feature Engineering: Created new features
- Imbalanced Data Handling: Tested SMOTE, ADASYN, Random Oversampling, and NearMiss techniques
- Model Evaluation: Compared 9 different models with hyperparameter tuning

## Best Model: Random Forest with Random Oversampling achieved 99.7% accuracy and 0.765 precision
