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
Welcome to the Predictive Modeling for Shark Tank Investment Deals repository. This project aims to predict the success of investment deals made on the popular TV show "Shark Tank." By employing various machine learning techniques, we analyze historical data to build models that can predict the outcome of investment opportunities presented on the show.

## Project Description
The project comprises two main components: Data Preprocessing and Predictive Modeling. We've implemented the entire project in Python, utilizing libraries such as scikit-learn for machine learning tasks and matplotlib for visualizations.

### Data Preprocessing
- Our dataset consists of data from past Shark Tank episodes, encompassing information about deals, entrepreneurs, and episodes.
- The preprocessing phase involves addressing missing values, engineering relevant features, performing one-hot encoding for categorical variables, and standardizing numerical attributes.
- We also delve into textual data, tokenizing it and calculating word frequency features based on deal outcomes.

### Predictive Modeling
- After splitting the preprocessed data into training and testing subsets, we apply various classification algorithms to construct predictive models. These algorithms include Logistic Regression, Linear Discriminant Analysis, Decision Tree Classifier, Naïve Bayes Model, K-Nearest Neighbors Model, Random Forest Model, and Gradient Boosting Model.
- We evaluate each model using essential performance metrics like precision, recall, F1-score, and AUC.
- To fine-tune our models, we employ hyperparameter tuning using GridSearchCV and RandomizedSearchCV.

### Results
- We compute accuracy scores for each model and present them.
- The results of hyperparameter tuning are displayed, showcasing the optimal parameters and cross-validation accuracies.
- We generate a bar plot that visually represents the AUC scores of the different models.

## Data
- Our dataset is sourced from [source link](https://example.com/dataset-link).

## Installation
1. Clone this repository: `git clone https://github.com/your-username/shark-tank-predictive-modeling.git`
2. Navigate to the project directory: `cd shark-tank-predictive-modeling`
3. Install the required dependencies: `pip install -r requirements.txt`

## Usage
1. Ensure that you possess the required dataset in CSV format.
2. Update the file path in the code to point to your dataset.
3. Run the provided Jupyter Notebook or Python script to execute the data preprocessing and predictive modeling stages.
4. Review the generated performance metrics, hyperparameter tuning results, and AUC score visualization.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- The dataset employed in this project is obtained from [source name](https://example.com/dataset-link).
- If you utilized any libraries or resources, kindly acknowledge them.

Feel free to customize the content of this README to match your project's specifics and structure. Include proper attributions, references, and relevant links.
