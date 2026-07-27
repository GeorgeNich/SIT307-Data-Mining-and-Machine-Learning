# Methodology review

The original project is substantial university work, but its reported performance should be interpreted cautiously.

## Strengths

- The project recognised impossible zero values in medical measurements.
- It compared mean and median imputation in relation to skewness.
- It used multiple feature-selection approaches.
- It compared several classification algorithms rather than relying on one model.
- It reported precision, recall, F1-score, confusion matrices and ROC-AUC in addition to accuracy.
- It discussed class imbalance and dataset limitations.

## Limitations in the original notebook

### Feature selection before final evaluation

Feature selection was performed using the full dataset before the final train/test evaluation. This allows information from records later treated as test data to influence feature selection.

### Hyperparameter tuning on test data

Several `GridSearchCV` objects were fitted using `Xtest` and `ytest`. The test set therefore influenced model selection and could not serve as an untouched final evaluation set.

### Transformations fitted on test data

`PowerTransformer().fit_transform(Xtest)` appears in tuning sections. A transformation should normally be fitted on training folds and then applied to held-out data through a pipeline.

### Preprocessing outside cross-validation

Imputation, outlier replacement and feature selection were not consistently contained inside cross-validation folds. This can make validation scores optimistic.

### Split consistency

The notebook creates multiple train/test variable sets with different test sizes, while later experiments reuse similarly named variables. This makes the experimental path harder to audit.

### Reproducibility

Some experiments use fixed random states, but the full workflow is not controlled by one reproducible configuration.

### Clinical framing

The dataset is observational and limited in size and population coverage. Model associations must not be described as proving medical causation or generalised to clinical diagnosis.

## Why the original work remains valuable

These limitations are normal learning points for a university project. Preserving them provides evidence of the original work and creates a clear basis for a later independent rebuild using modern validation practice.
