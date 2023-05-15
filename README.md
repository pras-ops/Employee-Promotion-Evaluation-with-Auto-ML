# Employee Promotion Evaluation with Auto ML

The main aim of this project is to predict whether an employee should be promoted or not, using Automated Machine Learning Techniques.

## Motivation

The HR team has stored data from the promotion cycle last year, which consists of details of all the employees in the company and whether they were promoted or not. However, the manual process of comparing and deciding promotions based on the available details is time-consuming and challenging due to the large amount of data.

## Problem Statement

We are given a dataset containing various attributes that can help us predict an employee's performance and whether they should be promoted. Using this data, we will build a model using AutoML techniques to automate the machine learning process.

## What is AutoML?

Automated Machine Learning (AutoML) is the process of automating the tasks involved in applying machine learning to real-world problems. In this project, we will be using EvalML, an open-source AutoML library written in Python, which automates a large part of the machine learning process and helps us evaluate which machine learning pipeline works best for the given dataset.

## Results

We have evaluated three machine learning algorithms on the dataset:

1. Decision Tree:
   - Confusion Matrix:
     [[7871  602]
      [ 433  370]]
   - Accuracy: 0.8884, Precision: 0.6643, Recall: 0.6949, F1: 0.6776, AUC: 0.6947

2. Logistic Regression:
   - Confusion Matrix:
     [[7871  602]
      [ 433  370]]
   - Accuracy: 0.8884, Precision: 0.6643, Recall: 0.6949, F1: 0.6776, AUC: 0.6947

3. Random Forest:
   - Confusion Matrix:
     [[8432   41]
      [ 523  280]]
   - Accuracy: 0.9392, Precision: 0.9069, Recall: 0.6719, F1: 0.7329, AUC: 0.7913

Feel free to explore the code and experiment with different models or parameters to improve the results.

