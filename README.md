# Employee Promotion Evaluation with AutoML

## Project Description
The main aim of this project is to predict whether an employee should be promoted or not, using Automated Machine Learning (AutoML) techniques. The project utilizes the EvalML library, an open-source AutoML library written in Python, which automates a large part of the machine learning process.

## Motivation
The HR team has stored data from the promotion cycle last year, which consists of details of all the employees in the company and whether they were promoted or not. However, due to the large amount of details available for each employee, it becomes difficult and time-consuming to compare and decide on promotions. This project aims to automate the process using machine learning techniques.

## Problem Statement
We are given a dataset containing various attributes that can help predict the performance of an employee and determine if they should be promoted. By building a model using AutoML techniques, we can streamline the decision-making process and improve efficiency.

## AutoML Overview
AutoML, or Automated Machine Learning, is the process of automating the tasks involved in applying machine learning to real-world problems. It automates the selection of machine learning pipelines and enables easy evaluation of different pipeline configurations for a given dataset.

For this project, we will be using the EvalML library, which is a powerful AutoML library in Python.

## Evaluation Results
The project evaluated several machine learning algorithms using EvalML. Here are the evaluation results for some of the algorithms:

### Decision Tree
- Confusion Matrix:
[[7871 602]
[ 433 370]]
- Accuracy: 0.8884
- Precision: 0.6643
- Recall: 0.6949
- F1: 0.6776
- AUC: 0.6947

### Logistic Regression
- Confusion Matrix:
[[7871 602]
[ 433 370]]
- Accuracy: 0.8884
- Precision: 0.6643
- Recall: 0.6949
- F1: 0.6776
- AUC: 0.6947

### Random Forest
- Confusion Matrix:
[[8432 41]
[ 523 280]]
- Accuracy: 0.9392
- Precision: 0.9069
- Recall: 0.6719
- F1: 0.7329
- AUC: 0.7913

### AutoML
The AutoML process ranked different machine learning pipelines based on their performance. Here are some of the top-ranked pipelines:

| Index | Pipeline Name | Ranking Score | Mean CV Score | Standard Deviation CV Score | Percent Better than Baseline |
|-------|---------------|---------------|---------------|-----------------------------|------------------------------|
| 0     | LightGBM Classifier w/ Label Encoder + Imputer + Undersampler + Select Columns Transformer | 0.2409 | 0.2409 | 0.0005 | 92.39% |
| 1     | XGBoost Classifier w/ Label Encoder + Imputer + Undersampler + Select Columns Transformer | 0.2421 | 0.2421 | 0.0017 | 92.35% |
| 2     | Elastic Net Classifier w/ Label Encoder + Imputer + Undersampler + Standard Scaler + Select Columns Transformer | 0.2698 | 0.2698 | 0.0013 | 91.47% |
| 3     | Logistic Regression Classifier w/ Label Encoder + Imputer + Undersampler + Standard Scaler + Select Columns Transformer | 0.2715 | 0.2715 | 0.0006 | 91.39% |
| 4     | Random Forest Classifier w/ Label Encoder + Imputer + Undersampler + Standard Scaler + Select Columns Transformer | 0.2743 | 0.2743 | 0.0009 | 91.26% |
