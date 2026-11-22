# Text Classification Using TF-IDF and Logistic Regression

## Project Overview

This project builds a text classification model using a cleaned text dataset.

The notebook compares a simple Baseline Model with a model that uses TF-IDF and Logistic Regression.

## Dataset

- File: `cleaned_dataset.csv`
- Number of records: 2,225
- Text column: `clean_text`
- Target column: `Label`
- Number of classes: 5

## Tools and Libraries

- Python
- Pandas
- Scikit-learn
- TF-IDF
- Logistic Regression

## Steps

1. Load and inspect the dataset.
2. Check data types, missing values, and duplicate rows.
3. Prepare the text and labels.
4. Split the data into training and testing sets (80% / 20%).
5. Train a Baseline Model using `DummyClassifier`.
6. Convert text into numerical features using `TfidfVectorizer`.
7. Train a Logistic Regression classifier.
8. Evaluate and compare the models.

## Evaluation

The notebook reports:

- Accuracy
- Precision
- Recall
- F1-score
- Classification report
- Confusion matrix

The baseline and model accuracy values are calculated when the notebook is run.

## Code Concepts

The notebook also demonstrates:

- Functions
- Docstrings
- Type hints
- Checking Python data types with `type()`
- Scikit-learn Pipeline

## How to Run

1. Keep `week5_day2_text_classification.ipynb` and `cleaned_dataset.csv` in the same folder.
2. Open the notebook in Jupyter Notebook or Google Colab.
3. Run the cells from top to bottom.
