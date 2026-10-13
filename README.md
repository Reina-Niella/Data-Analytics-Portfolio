# Data Analytics Portfolio

A collection of data analytics coursework covering Python fundamentals, exploratory data analysis (EDA), data visualization, and machine learning — built using pandas, scikit-learn, and Jupyter notebooks, applied to a real-world housing dataset.

## Contents

### 📊 Housing_EDA.ipynb
Exploratory Data Analysis on a housing dataset. Covers data loading, cleaning, descriptive statistics, and visualizations to uncover patterns and relationships in the data.

**Key techniques:**
- Data loading & inspection (`read_excel`, `head`, `info`, `describe`, `isnull`)
- Correlation analysis (`corr`) and correlation heatmaps
- Visualizations: histograms, scatter plots, bar charts, cross-tabulations (`crosstab`)

**Tools:** Python, pandas, numpy, matplotlib, seaborn, openpyxl, Jupyter

### 🤖 Housing_EDA_ML (2).ipynb
Machine learning applied to the same housing dataset — moving from exploring the data to building and evaluating predictive models.

**Key techniques:**
- Train/test splitting (`train_test_split`)
- Classification models: `KNeighborsClassifier`, `LogisticRegression`, `RandomForestClassifier`
- Regression models: `LinearRegression`, `RandomForestRegressor`, `KNeighborsRegressor`
- Hyperparameter tuning with `RandomizedSearchCV`
- Model evaluation: `f1_score`, `precision_score`, `recall_score`, `confusion_matrix`, `classification_report`
- ROC curve and AUC analysis (`RocCurveDisplay`)
- Feature importance

**Tools:** Python, pandas, numpy, matplotlib, seaborn, scikit-learn, Jupyter

### 📈 housing.ass.xlsx
Housing dataset used across the EDA and ML notebooks.

### 📝 BeTechified_Python_Assignment.docx
Python fundamentals assignment covering core programming concepts:
- Variables, lists, and dictionaries
- `for` loops
- Functions (including custom functions like `model_compare`)
- f-strings for formatted output
- Control flow and indentation

## Skills Demonstrated

- **Exploratory Data Analysis:** correlation analysis, heatmaps, histograms, scatter plots, bar charts
- **Machine Learning:** classification, regression, train/test splitting, hyperparameter tuning
- **Model Evaluation:** accuracy, precision, recall, F1 score, confusion matrices, ROC curves, AUC, feature importance
- **Python Fundamentals:** data structures, control flow, functions, string formatting

## About

This repository documents hands-on coursework from a Data Analytics program, progressing from foundational Python skills through exploratory data analysis to applied machine learning — all built around a real-world housing dataset.