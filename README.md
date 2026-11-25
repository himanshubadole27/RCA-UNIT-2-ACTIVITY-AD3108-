# RCA-UNIT-2-ACTIVITY-AD3108-
LOGISTIC REGRESSION 
# CIE 2 – Activity 2: Binary Classification Using Logistic Regression

## Overview
This project implements Logistic Regression for a binary classification problem. The model predicts the probability of a record belonging to one of two classes.

## Objective
- Understand Binary Classification using Logistic Regression.
- Train a model and obtain predicted probabilities.
- Convert probabilities into class labels using decision thresholds.
- Evaluate the model using classification metrics.
- Compare the model with a majority-class baseline.
- Study the effect of thresholds 0.3, 0.5 and 0.7.

## Dataset
- **Dataset:** Breast Cancer Wisconsin Dataset
- **Source:** Scikit-learn
- **Dataset link:** https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html
- **Class 0:** Benign
- **Class 1:** Malignant

### Features Used
- Mean Radius
- Mean Texture
- Mean Perimeter
- Mean Area
- Mean Smoothness
- Mean Concavity

## Methodology
1. Load and inspect the dataset.
2. Check missing values, duplicates and data types.
3. Visualize the class distribution.
4. Prepare features and target labels.
5. Split the dataset using stratified train-test splitting.
6. Scale numerical features.
7. Train the Logistic Regression model.
8. Generate predicted probabilities and class labels.
9. Evaluate using confusion matrix, accuracy, precision, recall, specificity and F1-score.
10. Calculate ROC-AUC and plot the ROC curve.
11. Compare with a majority-class baseline.
12. Analyze thresholds 0.3, 0.5 and 0.7.
13. Generate a new prediction and write the conclusion.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run all cells from top to bottom.
3. Review the generated plots, confusion matrix and evaluation metrics.

## Results
*Update this section after executing the notebook.*

- Accuracy: 92.11%
- Precision: 90.24%
- Recall: 88.10%
- Specificity: 94.44%
- F1-score: 0.8916
- ROC-AUC: 0.9821
- Recommended threshold: 0.3

## Conclusion
This activity demonstrates Binary Classification using Logistic Regression. The model is evaluated using multiple classification metrics and compared against a majority-class baseline. Different decision thresholds are tested to understand the trade-off between precision and recall.

The model is for educational purposes only and must not be used for medical diagnosis.

## GitHub Profile
https://github.com/complexiota
