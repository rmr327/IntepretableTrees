## Interpretable Trees
This project explores the application of various machine learning models, including RuleFit, Hierarchical Shrinkage Model, and RandomForestPlusRegressor, on two datasets: the California Housing dataset from sklearn and a high-stakes medical decision dataset from imodels.

## Introduction
This project aims to compare the performance and interpretability of different machine learning models on diverse datasets. The models include RuleFit, Hierarchical Shrinkage Model, and RandomForestPlusRegressor.

## Datasets
California Housing Dataset
Source: sklearn
Description: This dataset contains information collected from the 1990 California census. It includes features such as median house value, median income, and other demographic information.

High-Stakes Medical Decision Dataset
Source: imodels
Description: This dataset is used for making critical medical decisions. It includes various medical features and outcomes that are crucial for model evaluation.

## Models

> RuleFit Algorithm
Description: RuleFit is a model that combines the predictive power of decision trees with the interpretability of linear models. It generates rules from decision trees and then fits a sparse linear model to these rules.
Flowchart:

![image](https://github.com/user-attachments/assets/740b7905-f3eb-422d-9cb6-8189187a280a)


> Hierarchical Shrinkage Model
Description: This model applies hierarchical shrinkage to improve the stability and interpretability of the estimates. It is particularly useful for high-dimensional data where traditional models may overfit.
Flowchart:

![image](https://github.com/user-attachments/assets/0904faec-a286-4a6e-bf82-598cde30f9b8)


> Random Forest Plus Regressor
Description: An enhanced version of the traditional RandomForestRegressor, this model includes additional features for better performance and interpretability.
Flowchart:

![image](https://github.com/user-attachments/assets/04c707ae-9e82-40ca-a95f-0c36a632ca6e)
