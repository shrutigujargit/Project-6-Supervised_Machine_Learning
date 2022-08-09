# Project-6-Supervised_Machine_Learning
>## Predicting housing prices

You work for a consultancy specialising in real estate: your clients include developers, agencies, and investors. Pricing is a central aspect to the business. Traditionally, it’s the domain of home appraisers to determine the value of a property, which must be executed in an unbiased way, following an official criteria to ensure that there is no bias towards neither the buyer nor the seller.

For each house, it also contains around 80 different features, such as the area, the state of the property, whether it has a backyard or not, etc.

>### Tasks:
* Create a model to predict whether a house is expensive or not (Classification)

* Create a model to predict the exact price of a house (Regression)

> ### Summary of work done so far:
* In the first phase, the model you build will have a categorical target: “Expensive” and “Not expensive”. Whenever a ML task involves a categorical target variable, it is called a classification task.

* In the second phase of the project, the target variable will be numerical (the exact prices of the houses in dollars): you will be dealing with a regression task.

The approach followed was as following:
1. Understand the Data
2. Exploratory Data Analysis and Data cleaning
3. Data Preprocessing
   * Encoding Using Pipelines
   * Simple Imputer and One Hot Encoder
   * Data Scaling using MinMaxScaler & StandardScaler
   * used Column Transformer
4. Modelling: 
   * Decision Tree Classifier
   * Random Forest Classifier
   * K neighbours Classifier
   * Linear Regression
   * Random Forest Regressor
5. Error Analysis
6. Implemention of the Solution

>## Mushroom Project Competition:
Prediction of poisionous Mushrooms based on the provided Database. Main Goal of this Project was to have minimum False Negatives.


