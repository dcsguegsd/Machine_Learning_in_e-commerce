# Machine Learning Models for Predicting Purchase Decisions in E-commerce

## Project Overview
This project analyzes the potential of selected machine learning models to predict purchase decisions in the e-commerce sector. The study focuses on identifying which classification model most effectively detects purchasing sessions and which behavioral factors influence the likelihood of a transaction.

The project was developed as part of a master's thesis and combines elements of web analytics, machine learning, and data analysis.

## Research Objective
The main objective of the study is to evaluate the effectiveness of selected machine learning models in predicting purchase decisions during user sessions in an online store.

The key research problem is determining which model identifies the largest number of purchasing users using real-world behavioral data.

Additionally, the analysis aims to identify which user behaviors have the strongest impact on purchase conversion.

## Dataset
The dataset consists of user sessions described by behavioral, technical, and temporal features.

Each observation represents a single user session and contains information about:
- user behavior during the session
- technical session attributes
- time-related variables
- whether the session ended with a purchase

This allows the problem to be formulated as a binary classification task.

## Project Structure

Preprocessing.ipynb  
Data cleaning, feature preparation, exploratory data analysis (EDA), basic statistical analysis, correlation matrix and data preprocessing.

1_LogisticRegression.ipynb  
Logistic Regression model implementation.

2_KNN.ipynb  
K-Nearest Neighbors classification model.

3_DecisionTree.ipynb  
Decision Tree model.

4_GradientBoosting.ipynb  
Gradient Boosting model.

Dataset.xlsx 
Original dataset containing raw user session data used for the analysis.

Dataset_after_cleaning.xlsx
Cleaned dataset after preprocessing, including feature preparation and data ready for machine learning models.

Visualizations/  
Data exploration and visualizations.

Report.html  
Basic statistical report.

## Methodology
The project includes the following analytical steps:

1. Data exploration and preprocessing
2. Feature preparation and transformation
3. Training of classification models
4. Model performance evaluation
5. Interpretation of results

Special attention was given to the issue of class imbalance in the dataset.

## Machine Learning Models
The following algorithms were used:

- Logistic Regression
- K-Nearest Neighbors
- Decision Tree
- Gradient Boosting

Model performance was evaluated using standard classification metrics.

## Tools and Technologies

Python environment with the following libraries:

- pandas
- numpy
- scikit-learn
- SHAP
- matplotlib

## Results
The models were compared in terms of their ability to identify purchasing sessions and analyze the factors influencing conversion probability.

The results provide insight into how user behavior during an online session affects the likelihood of making a purchase.

## Project Type
Master's thesis project focused on the application of machine learning methods in web analytics and e-commerce data analysis.


## How to run the project:
1. Download the repository
2. Install required libraries
3. Run notebooks in Jupyter
