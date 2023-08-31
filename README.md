# Predictive Modeling for Shark Tank Investment Deals

![Shark Tank](https://github.com/VedantMandre/SharkTank_Analysis/assets/114442140/63069e81-b36f-4537-b36a-5641c75b88fa)

## Table of Contents
- [Introduction](#introduction)
- [Project Description](#project-description)
- [Data](#data)

## Introduction
Welcome to the Predictive Modeling for Shark Tank Investment Deals repository. This project aims to predict the success of investment deals made on the popular TV show "Shark Tank." By utilizing various machine learning techniques, I analyze historical data to build models capable of predicting the outcome of investment opportunities presented on the show.

## Project Description
The project consists of two main components: Data Preprocessing and Predictive Modeling. I've implemented the entire project in Python, using libraries such as scikit-learn for machine learning tasks and matplotlib for visualizations.

### Data Preprocessing
- My dataset comprises data from past Shark Tank episodes, containing information about deals, entrepreneurs, and episodes.
- During the preprocessing phase, I handle missing values, engineer relevant features, perform one-hot encoding for categorical variables, and standardize numerical attributes.
- I also delve into textual data, tokenize it, and calculate word frequency features based on deal outcomes.

### Predictive Modeling
- After splitting the preprocessed data into training and testing subsets, I apply various classification algorithms to build predictive models. These algorithms include Logistic Regression, Linear Discriminant Analysis, Decision Tree Classifier, Naïve Bayes Model, K-Nearest Neighbors Model, Random Forest Model, and Gradient Boosting Model.
- I evaluate each model using essential performance metrics such as precision, recall, F1-score, and AUC.
- To fine-tune my models, I employ hyperparameter tuning using GridSearchCV and RandomizedSearchCV.

### Results
- I compute accuracy scores for each model and present them.
- The results of hyperparameter tuning are displayed, showcasing the optimal parameters and cross-validation accuracies.
- I generate a bar plot to visually represent the AUC scores of the different models.

## Data
- My dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/ulrikthygepedersen/shark-tank-companies).

Feel free to customize the content of this README to match your project's specifics and structure. Include proper attributions, references, and relevant links.
