Red Wine Quality Prediction 

Overview

Welcome to the Red Wine Quality Prediction project! This repository contains the code for performing data preprocessing, exploratory data analysis, and building  machine learning models to predict quality of red wine.
Dataset

The dataset contains various features like  fixed acidity,volatile acidity,citric acid ,residual sugar etc. The target variable is the quality of wine.

Project Workflow

1.Exploratory Data Analysis: Visualizing the data to identify patterns and relationships. 

We use various plots and statistical methods to understand the data:

Bar Plots: To verify the quality with each of the feature given 
  
Correlation Heatmap: To identify the strength of relationships between different features and the target variable. 

 2.Data Preparation: Use of lambda and apply function to convert the quality parameter to binary function (0 or 1)

3. Model Building:Random Forest Classifier: Labeled target variable is classified into classes by the classifier .

4. Results:Random Forest Classifier predicts the quality of wine as a binary classifier 0(bad qaulity ) and 1(good quality) with accuracy of 93%.
