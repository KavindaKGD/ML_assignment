# Machine Learning Assignment

## Project Title
White Wine Quality Classification using Supervised Machine Learning

## Problem Statement
Wine quality is an important factor in the food and beverage industry. The objective of this project is to predict whether a white wine sample is of good quality or poor quality based on its physicochemical properties. This was treated as a supervised classification problem using four different machine learning algorithms.

## Dataset
The dataset used for this project is the **White Wine Quality Dataset** obtained from the **UCI Machine Learning Repository**.

- Dataset Name: Wine Quality Dataset (White Wine)
- Source: UCI Machine Learning Repository
- Link: http://archive.ics.uci.edu/ml/datasets/wine+quality

The dataset contains physicochemical measurements of white wine samples, such as acidity, sugar, chlorides, sulphates, alcohol content, and other chemical properties. The target variable is `quality`.

## Project Objective
The main objective of this project is to compare the performance of four supervised machine learning algorithms in predicting white wine quality and identify the best-performing model.

## Machine Learning Approach
This project was carried out as a **supervised learning classification problem**.

The original `quality` score was converted into a binary classification target:
- `1` = Good quality wine (`quality >= 6`)
- `0` = Poor quality wine (`quality < 6`)

## Algorithms Used
The following four machine learning algorithms were applied:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K-Nearest Neighbors (KNN)

## Project Structure
```bash
ml-assignment/
│
├── README.md
├── data/
├── notebooks/
│   ├── data_preprocessing.ipynb
│   ├── model_1_logistic_regression.ipynb
│   ├── model_2_decision_tree.ipynb
│   ├── model_3_random_forest.ipynb
│   ├── model_4_knn.ipynb
│   └── model_comparison.ipynb
└── report/