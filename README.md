# Spam Detection Project

## Overview
This project is a supervised machine learning model for SMS spam detection using Python and Scikit-learn.

The project compares:
- Logistic Regression
- Naive Bayes

The dataset is preprocessed using TF-IDF vectorization and evaluated using multiple classification metrics.

## Dataset
Dataset used:
- spam.csv

Columns:
- v1 → Label (ham/spam)
- v2 → Message text

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

spam_detection_project/

├── imports.py  
├── preprocessing.py  
├── logistic_regression_model.py  
├── naive_bayes_model.py  
├── main.py  
├── spam.csv  
├── spam_detection_project_notebook.ipynb  
├── spam_detection_project_outputs_notebook.ipynb  
├── spam_detection_project_report.txt  
├── output.png  
└── output2.png  

## Installation

```bash
pip install pandas numpy scikit-learn matplotlib seaborn notebook
```

## Run Project

```bash
python preprocessing.py
```

```bash
python logistic_regression_model.py
```

```bash
python naive_bayes_model.py
```

```bash
python main.py
```

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Cross Validation Accuracy

## Results
Both models achieved high accuracy for spam classification.

Naive Bayes performed slightly better on spam message detection.

## Outputs
- Classification reports
- Accuracy scores
- Confusion matrix plots
- Cross-validation scores

## Author
Mohammed Talha Hussain
