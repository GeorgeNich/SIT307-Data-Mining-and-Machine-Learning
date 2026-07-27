# Individual Problem-Solving Portfolio

This section preserves George Nicholson's individual SIT307 work. It shows the progression from introductory Python exercises and working with common data formats to data preparation, statistical analysis and machine-learning techniques.

The folders are deliberately simple: each link below opens the actual notebook, spreadsheet or written response rather than another navigation page.

## Python and data foundations

| Area | What it demonstrates | Open the work |
|---|---|---|
| Python problem solving | Functions, filtering, conditionals, BMI calculation and triangle classification | [Notebook](01-python-problem-solving/python-problem-solving.ipynb) |
| Data visualisation | Descriptive statistics, box plots, histograms and scatter plots using the Iris dataset | [Notebook](02-data-visualisation/iris-visualisation.ipynb) · [Dataset](02-data-visualisation/data/iris.txt) |
| NumPy data handling | Loading and working with text, CSV and JSON data | [Notebook](03-data-loading-and-manipulation/numpy-data-handling.ipynb) |
| Pandas data handling | CSV, text, JSON, Excel, pickle and SQLite workflows | [Notebook](03-data-loading-and-manipulation/pandas-data-handling.ipynb) |

## Data analysis and machine learning

| Area | What it demonstrates | Open the work |
|---|---|---|
| Data cleaning | Missing values, anomalous entries and cleaning decisions | [Notebook](04-data-cleaning/data-cleaning.ipynb) · [Dataset](04-data-cleaning/data/Week%204_data.csv) |
| Correlation and PCA | Discretisation, correlation analysis and dimensionality reduction | [Notebook](05-correlation-and-pca/correlation-discretisation-and-pca.ipynb) |
| Decision trees | Tree induction, evaluation and validation strategies | [Induction](06-decision-trees-and-validation/decision-tree-induction.ipynb) · [Validation](06-decision-trees-and-validation/decision-tree-validation.ipynb) |
| Regression | Linear and logistic-regression problem solving | [Notebook](07-regression/regression-problem-solving.ipynb) |
| Neural networks | Breast-cancer classification with a multilayer perceptron | [Notebook](08-neural-networks/breast-cancer-mlp.ipynb) |

## Manual calculations and written responses

- [Z-score and outlier workings](09-manual-calculations/z-score-workings.xlsx)
- [Pearson correlation workings](09-manual-calculations/pearson-correlation.xlsx)
- [Spearman correlation workings](09-manual-calculations/spearman-correlation.xlsx)
- [Information gain and cross-validation responses](09-manual-calculations/information-gain-and-cross-validation.pdf)
- [Regression workings](09-manual-calculations/regression-workings.xlsx)
- [Neural-network calculations](09-manual-calculations/neural-network-workings.pdf)

## Historical compatibility notes

The original notebook logic and outputs are preserved.

- The Pandas data-handling and data-cleaning notebooks use Windows-style paths such as `data\ex1.csv` and `data\Week 4_data.csv`; path separators may need adjustment on macOS or Linux.
- The regression notebook imports scikit-learn's removed `load_boston` dataset and therefore requires an older compatible environment or a later documented replacement.
- Some exercises contain university-era methodological or implementation issues. These are retained as historical work rather than silently corrected.

[Return to the repository overview](../)
