## House Price Prediction - Data analysis - Udacity Project 1

### Table of Content
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)

## Installation <a name="installation"></a>

this shoud run smoothly in python 3, but you to install the following libraries and tools if they are not installed:
* Numpy
* Pandas
* Matplotlib
* sklearn
* IPython
* Seaborn
* Math
* Tabulate

## Project Motivation<a name="motivation"></a>

This project is aimed to present some information about house pricing and what factors the pricing depends on,and the goal of this statistical analysis is to help us understand the relationship between house features and how these variables are used to predict house price. Also, to present some data visualization figures that help the public to understand the prices change from house to another and why.

This project is consist of three main business questions:
* What are the expected house features for average prices based on our analysis?
* What are the most effective house features in pricing?
* How well can we predict the house pricing ?

## File Descriptions <a name="files"></a>
  
* house_data.csv

  This file is the dataset that used in this project, dataset link https://www.kaggle.com/vasugarg/house-price-prediction, The dataset is consisted of historic data of houses     sold between May 2014 to May 2015 in Washington state
* project.ipybn

  This file contains all the work that are done to present all data visualization figures and prediction results.
  
  
## Results<a name="results"></a>

This project provides answers for our raised questions. Starting with cleaning and filtering our data and run it into some processes, in order to answer our business question. We are able to predict the the features of averagely priced housed, find the most effective features that influence the pricing are the house grading and lot area, and design a model to be able to predict 69.3% of house pricing using Linear reggression and 83% using RandomForestRegressor.

The main findings of the code can be found at the post available [here](https://medium.com/@abdalwahab.alessa/house-price-prediction-298b38b38636)






