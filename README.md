# Iris Dataset Understanding

## Dataset Overview

The Iris dataset is a classic dataset from the UCI Machine Learning Repository and is widely used in statistics and machine learning as an introductory dataset for classification tasks.[web:1][web:3][web:7][web:11][web:15]  
It contains measurements of iris flowers collected by R. A. Fisher and is designed to distinguish different iris species based on their flower characteristics.[web:1][web:3][web:7][web:11]

## Purpose of the Dataset

The main purpose of the Iris dataset is to support the development and evaluation of classification models.[web:1][web:3][web:7][web:11]  
In this dataset, the target variable is the iris species, and a machine learning model can use the flower measurements to predict whether a plant belongs to Iris setosa, Iris versicolor, or Iris virginica.[web:1][web:3][web:7][web:11]

## Key Features

The dataset contains 150 instances, where each instance represents one iris plant.[web:1][web:3][web:7][web:11]  
There are four main numerical input features, all measured in centimetres:[web:1][web:3][web:7][web:11]  

- Sepal length (cm) – length of the outer sepal. [web:1][web:3][web:7][web:11]  
- Sepal width (cm) – width of the outer sepal. [web:1][web:3][web:7][web:11]  
- Petal length (cm) – length of the inner petal. [web:1][web:3][web:7][web:11]  
- Petal width (cm) – width of the inner petal.[web:1][web:3][web:7][web:11]  

The target feature is the **class** label, with three possible species: *Iris setosa*, *Iris versicolor*, and *Iris virginica* (50 samples for each class).[web:1][web:3][web:7][web:11]

## Notable Observations

The species *Iris setosa* is linearly separable from the other two species when using petal measurements, which makes the dataset suitable for illustrating simple linear classifiers.[web:1][web:3]  
*Iris versicolor* and *Iris virginica* overlap more in their sepal measurements, creating a slightly more complex decision boundary and making classification between these two classes more challenging.[web:1][web:3][web:7][web:11]
