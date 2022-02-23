# Heart Failure Prediction

Russell Peavey

## Abstract

An example workflow demonstrating use of pandas for data processing and sklearn for modeling and evaluation.

## Data

Row ordered anonymized clinical patient data of 4000 patients with ~1500 different diagnosis codes across provider visits from [MIMIC-III](https://www.nature.com/articles/sdata201635)


## Feature Engineering

- SVMLight format of diagnosis code counts, min-maxed normalized, in patient observation window


## Models

- Decision Tree
- Logistic Regression
- SVM

## Evaluation

K-fold and randomized K-fold methods.
- F1 score
- Accuracy
- Precision
- Recall
