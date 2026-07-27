# Pima Diabetes Analysis and Classification

This project examined diabetes outcomes in the Pima Indians Diabetes dataset through exploratory analysis and supervised classification.

## Open the work

| Stage | Contributors | Notebook | Report | Dataset |
|---|---|---|---|---|
| Exploratory analysis | George Nicholson, Anthony Trinh, Jamil Rizkallah and Jet Hall | [Open notebook](exploratory-analysis/pima-diabetes-exploratory-analysis.ipynb) | [Open report](exploratory-analysis/assignment-2-report.pdf) | [Open data](exploratory-analysis/diabetes.csv) |
| Machine-learning comparison | George Nicholson and Anthony Trinh | [Open notebook](machine-learning/pima-diabetes-model-comparison.ipynb) | [Open report](machine-learning/assignment-3-report.pdf) | [Open data](machine-learning/diabetes.csv) |

## Stage 1: exploratory analysis

The first stage covered:

- impossible zero values in medical measurements
- missing and anomalous data
- mean or median imputation based on distribution shape
- z-score outlier analysis
- univariate and multivariate visualisation
- correlation analysis
- principal component analysis
- comparisons between raw and cleaned data

## Stage 2: machine-learning comparison

The second stage covered:

- ANOVA, chi-square and information-gain feature selection
- Logistic Regression
- K-Nearest Neighbours
- Gaussian Naive Bayes
- Decision Tree
- Support Vector Machine
- cross-validation and hyperparameter-search experiments
- confusion matrices, precision, recall, F1-score and ROC-AUC

## Historical findings

The final report identified Gaussian Naive Bayes as the strongest principal model discussed, recording 173 correct predictions from 231 test cases, or about 75% accuracy. The notebook contains additional tuning experiments approaching 79%.

These are preserved historical results rather than current benchmark claims. The original methodology contains validation limitations that should be considered when interpreting the numbers.

- [Read the authorship record](AUTHORSHIP.md)
- [Read the methodology review](methodology-review.md)
- [Read the future independent rebuild roadmap](../future-independent-rebuild/)

## Dataset note

The dataset is stored beside each notebook because the original notebooks load `diabetes.csv` from their working directory. The source archive did not include a definitive dataset-licence statement, so the original source terms should be confirmed before reuse.

## Medical disclaimer

This is historical university coursework and must not be used for clinical diagnosis or medical decision-making.
