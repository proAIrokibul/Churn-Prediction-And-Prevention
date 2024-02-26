## Predictive Churn Analysis
## Overview
This repository contains Python code for predictive churn analysis in a telecom industry setting. The purpose of this project is to develop a predictive model to identify potential churn customers and analyze factors contributing to customer attrition. The analysis includes exploratory data visualization, statistical summaries, and the implementation of a machine learning model using the RandomForestClassifier.

##Key Features

- Data Exploration: Utilizes pandas, numpy, seaborn, and matplotlib for exploratory data analysis, including descriptive statistics and visualizations.
- Categorical Analysis: Investigates the distribution of categorical variables, pie charts showcasing category proportions, and radar charts comparing features across different categories.
- Numerical Feature Distribution: Utilizes histograms to visualize the distribution of numerical features such as tenure, monthly charges, and total charges.
- Churn-Related Box Plots: Employs box plots to analyze the distribution of tenure and monthly charges concerning customer churn.
- Machine Learning Model: Develops a predictive model using RandomForestClassifier from scikit-learn, with preprocessing steps including imputation and one-hot encoding.
- Model Evaluation: Assesses the model's accuracy on a test set, providing insights into its predictive performance.

## Usage

- Dataset: Ensure the dataset is available and correctly linked in the code (current dataset: "Churn_dataset.csv").
- Exploratory Data Analysis: Execute code blocks for data exploration, visualization, and numerical summaries.
- Machine Learning Model: Run the code for preprocessing and training the RandomForestClassifier for churn prediction.
- Model Evaluation: Evaluate the accuracy of the predictive model on the provided test set.

## Dependencies
- numpy
- scipy
- pandas
- seaborn
- matplotlib
- scikit-learn
