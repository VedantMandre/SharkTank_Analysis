# Predictive Modeling for Shark Tank Investment Deals

![Shark Tank](https://github.com/VedantMandre/SharkTank_Analysis/assets/114442140/63069e81-b36f-4537-b36a-5641c75b88fa)

## Table of Contents
- [Introduction](#introduction)
- [Project Description](#project-description)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)
- [Acknowledgements](#acknowledgements)

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

## Installation
1. Clone this repository: `git clone https://github.com/your-username/shark-tank-predictive-modeling.git`
2. Navigate to the project directory: `cd shark-tank-predictive-modeling`
3. Install the required dependencies: `pip install -r requirements.txt`

## Usage
1. Make sure you have the required dataset in CSV format.
2. Update the file path in the code to point to your dataset.
3. Run the provided Jupyter Notebook or Python script to execute the data preprocessing and predictive modeling stages.
4. Review the generated performance metrics, hyperparameter tuning results, and AUC score visualization.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- The dataset used in this project is obtained from [Kaggle](https://www.kaggle.com/datasets/ulrikthygepedersen/shark-tank-companies).
- If you used any libraries or resources, please acknowledge them.

Feel free to customize the content of this README to match your project's specifics and structure. Include proper attributions, references, and relevant links.
