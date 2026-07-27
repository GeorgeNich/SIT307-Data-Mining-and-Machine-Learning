# Future Independent Pima Diabetes Rebuild

After publishing the historical coursework, George Nicholson plans to rebuild the Pima Diabetes project independently.

## Goal

Create a reproducible, leakage-free classification study and determine whether the original performance can be improved honestly. A higher score is useful only when supported by sound validation.

## Planned approach

- keep an untouched final test set
- use stratified splitting
- place imputation, scaling and feature selection inside scikit-learn pipelines
- tune models only on training data
- use repeated or nested cross-validation where practical
- fix random seeds and record the software environment
- compare against a simple baseline
- evaluate accuracy, ROC-AUC, precision, recall, F1-score and calibration
- consider the cost of false negatives in a screening context
- compare all-feature and selected-feature models
- document uncertainty and limitations

Potential models include Logistic Regression, K-Nearest Neighbours, Gaussian Naive Bayes, Support Vector Machine, Random Forest and Gradient Boosting.

No rebuilt code is presented here yet. This page records the planned next project and keeps it separate from the original group submission.
