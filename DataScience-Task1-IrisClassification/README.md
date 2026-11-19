# Task 1 - Iris Flower Classification

**Intern:** Farah Bounouara | **Track:** Data Science | **Oasis Infobyte (OIBSIP)**

## Objective
Train machine learning models to predict the species of an iris flower (Setosa, Versicolor, Virginica) from its measurements.

## Dataset
Iris dataset loaded from `sklearn.datasets.load_iris()` (150 samples, 4 features, 3 balanced classes).

## What was done
- Exploratory data analysis: shape, data types, missing values, descriptive statistics
- Visualizations: pairplot and boxplots by species
- 80/20 stratified train/test split
- Three classifiers: Logistic Regression, KNN, Random Forest
- Evaluation: accuracy, confusion matrix, classification report, 5-fold cross-validation

## Results
| Model | Test accuracy | 5-fold CV accuracy |
|---|---|---|
| KNN | 1.000 | 0.973 |
| Logistic Regression | 0.967 | 0.973 |
| Random Forest | 0.900 | 0.967 |

KNN gave the best test score, but cross-validation shows the three models are very close.

## How to run
Open `iris_classification.ipynb` in Google Colab or Jupyter and run all cells.

## Tools
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, Google Colab
