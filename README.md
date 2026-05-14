# Titanic Survival Prediction

A machine learning project to predict whether a passenger survived the Titanic disaster.

## Problem
Binary Classification — Predict `Survived` (0 = No, 1 = Yes)

## Dataset
[Titanic - Kaggle](https://www.kaggle.com/competitions/titanic/data)  
891 rows | 12 features

## Approach
- EDA: survival patterns by gender, age, fare
- Preprocessing: median imputation, standard scaling, one-hot encoding
- Model: Random Forest Classifier (100 estimators)
- Full sklearn Pipeline to prevent data leakage

## Results
| Metric | Score |
|---|---|
| Accuracy | 82% |
| F1 Score | 0.77 |
| Precision | ~0.79 |
| Recall | ~0.75 |

## What I Learned
- Pipelines prevent data leakage cleanly
- Gender and Pclass are strongest survival predictors
- Fare outlier capping improved model stability

## How to Run
1. Clone repo
2. Place `Titanic.csv` in root folder
3. Open `notebook.ipynb` and run all cells

## Tech Stack
`Python` `pandas` `scikit-learn` `matplotlib` `seaborn`
