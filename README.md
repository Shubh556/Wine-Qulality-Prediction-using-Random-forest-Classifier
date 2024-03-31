# Wine Quality Prediction

## Overview

This project aims to predict the quality of red wine based on its chemical properties using machine learning techniques. It involves analyzing a dataset containing various attributes of red wine samples and building a predictive model to classify wines as good or bad quality.

## Dataset

The dataset used in this project is named "winequality-red.csv".
It comprises 1599 samples of red wine, each with 11 attributes and a target variable, quality.

## Attributes

1.Fixed Acidity: The concentration of non-volatile acids in the wine.

2.Volatile Acidity: The amount of acetic acid in the wine, which can lead to an unpleasant vinegar taste.

3.Citric Acid: The presence of citric acid, which can add freshness and flavor to the wine.

4.Residual Sugar: The amount of sugar remaining in the wine after fermentation, influencing its sweetness.

5.Chlorides: The amount of salt in the wine, which affects its taste and mouthfeel.

6.Free Sulfur Dioxide: The presence of sulfur dioxide, which acts as a preservative and antimicrobial agent.

7.Total Sulfur Dioxide: The total amount of sulfur dioxide present in the wine.

8.Density: The density of the wine, which is related to its alcohol content and sweetness.

9.pH: The acidity or alkalinity of the wine.

10.Sulphates: The presence of sulfur compounds, which can contribute to wine preservation and aroma.

11.Alcohol: The alcohol content of the wine.

## Analysis and Visualization

1.Exploratory Data Analysis (EDA) is performed to understand the distribution and relationships between different features and the target variable.

2.Visualizations such as histograms and barplots are used to illustrate the characteristics of the dataset.

## Preprocessing

1.Label Binarization: The target variable "quality" is binarized into two categories, representing good (quality >= 7) and bad (quality < 7) wine quality.

2.Train Test Split: The dataset is split into training and testing sets to train the model and evaluate its performance.

## Model Training

Random Forest Classifier is selected as the predictive model due to its ability to handle high-dimensional data and nonlinear relationships.The model is trained on the training set.

## Evaluation

The accuracy score is computed on the test set to assess the performance of the trained model.

## Predictive System

An example predictive system is implemented to demonstrate how the trained model can predict the quality of a new wine sample based on its chemical properties.Users input the features of the wine, and the model predicts whether it is of good or bad quality.