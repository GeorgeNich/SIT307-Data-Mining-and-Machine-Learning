# SIT307 Data Mining and Machine Learning

A curated portfolio of data-mining and machine-learning work completed for Deakin University's SIT307 unit.

The repository combines a two-stage group project examining diabetes outcomes with an individual problem-solving portfolio covering data preparation, visualisation, dimensionality reduction, regression, decision trees, validation and neural networks.

## Featured Project: Pima Diabetes Analysis and Classification

The flagship project follows the Pima Indians Diabetes dataset through two connected stages:

1. **Exploratory analysis** completed by George Nicholson, Anthony Trinh, Jamil Rizkallah and Jet Hall.
2. **Machine-learning comparison** completed by George Nicholson and Anthony Trinh.

The project covers:

- missing and anomalous medical values
- data cleaning and imputation
- univariate and multivariate visualisation
- correlation analysis
- principal component analysis
- feature-selection experiments
- Logistic Regression
- K-Nearest Neighbours
- Gaussian Naive Bayes
- Decision Trees
- Support Vector Machines
- cross-validation and hyperparameter experiments
- confusion matrices, precision, recall, F1-score and ROC-AUC

**[View the complete Pima Diabetes project →](pima-diabetes-project/)**

Direct evidence:

- [Exploratory-analysis notebook](pima-diabetes-project/exploratory-analysis/pima-diabetes-exploratory-analysis.ipynb)
- [Exploratory-analysis report](pima-diabetes-project/exploratory-analysis/assignment-2-report.pdf)
- [Machine-learning notebook](pima-diabetes-project/machine-learning/pima-diabetes-model-comparison.ipynb)
- [Machine-learning report](pima-diabetes-project/machine-learning/assignment-3-report.pdf)
- [Authorship record](pima-diabetes-project/AUTHORSHIP.md)
- [Methodology review](pima-diabetes-project/methodology-review.md)

## Featured Individual Work: Breast Cancer Neural-Network Classification

An individual machine-learning exercise using a multilayer perceptron neural network to classify breast-tumour samples as malignant or benign.

The notebook demonstrates:

- feature scaling
- training and test separation
- multilayer perceptron configuration
- hidden-layer experiments
- momentum and regularisation experiments
- confusion-matrix analysis
- classification evaluation

**[View the Breast Cancer MLP notebook →](individual-work/08-neural-networks/breast-cancer-mlp.ipynb)**

This is an educational classification exercise using an established dataset. It is not a clinical cancer-detection system.

## Individual problem-solving portfolio

The individual work shows my progression from introductory Python programming and data handling through data cleaning, visualisation, statistical analysis, model validation and neural networks.

**[Explore the complete individual portfolio →](individual-work/)**

### Highlighted individual work

- [Breast Cancer MLP classification](individual-work/08-neural-networks/breast-cancer-mlp.ipynb) — neural-network classification, feature scaling, parameter experiments and evaluation.
- [Decision-tree validation](individual-work/06-decision-trees-and-validation/decision-tree-validation.ipynb) — decision-tree training, tree-depth analysis, cross-validation, stratified folds and shuffle-split evaluation.
- [Regression problem solving](individual-work/07-regression/regression-problem-solving.ipynb) — linear regression, logistic regression, error analysis and model comparison.
- [Correlation, discretisation and PCA](individual-work/05-correlation-and-pca/correlation-discretisation-and-pca.ipynb) — correlation analysis, outlier treatment, discretisation and dimensionality reduction.
- [Data cleaning](individual-work/04-data-cleaning/data-cleaning.ipynb) — identification and treatment of missing, anomalous and inconsistent data.
- [Pandas data handling](individual-work/03-data-loading-and-manipulation/pandas-data-handling.ipynb) — loading, manipulating and inspecting structured data.
- [Iris data visualisation](individual-work/02-data-visualisation/iris-visualisation.ipynb) — introductory visual exploration of a labelled dataset.

The portfolio also contains manual calculations and supporting exercises demonstrating the theory behind correlation, information gain, regression and neural-network operations.

## Future improvement

A later independent rebuild is planned to repeat the Pima Diabetes study using:

- leakage-free preprocessing pipelines
- clearly separated training, validation and test data
- reproducible random seeds and environments
- stronger cross-validation
- consistent model-selection criteria
- transparent comparison against simple baselines
- more careful interpretation of medical classification metrics

**[Read the independent rebuild roadmap →](future-independent-rebuild/)**

## Historical status

The notebooks and reports are preserved as university coursework from 2022. Their analytical logic has not been silently rewritten.

Some notebooks rely on older libraries, locally stored datasets or Windows-style file paths. The original work also contains methodological and reproducibility limitations that are documented rather than hidden.

Results shown in the notebooks are preserved historical coursework outcomes, not current benchmark claims.

## Disclaimer

This repository contains educational machine-learning work.

The diabetes and breast-cancer datasets and models must not be used for clinical diagnosis, medical decisions or individual health predictions.
