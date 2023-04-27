# Machine Learning Project

This project was carried out by a team of four people during the Data Science Master's program at Assembler Institute in the October 2022/23 promotion.
It was the first project of the data science module in **Assembler's Data Science** master's degree supervised and corrected by Juan Manuel Moreno.

## Introduction

The objective of the problem is to predict if a person has a salary of more than 50 thousand dollars per year or not, based on their characteristics.

We made use of the adult data set. This data set comes from the following University of California Irvine Track (Url:https://archive.ics.uci.edu/ml/datasets/Census+Income)

**Data set description**:

It has a total of 14 predictor variables X and a continuous variable to predict Y.
The total number of samples is 32561 people.

Variable information:

Dependent variables Y

- TARGET: >50K, <=50K.

Independent variables X:

- Age: continuous.
- Work class: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
- fnlwgt: continuous.
- Education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool .
- Education-num: continuous.
- Marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
- Occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house -serv, Protective-serv, Armed-Forces.
- Relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
- Race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
- Sex: Female, Male.
- Capital-gain: continuous.
- Capital-loss: continuous.
- Hours-per-week: continuous.
- Native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US (Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holland-Netherlands.

## Objectives of this project

- Correctly treat the characteristics of a data set according to its type (numeric, categorical).
- Transform data to remove outliers, code categorical features, or create new columns.
- Handle null values.
- Differentiate the main models of supervised learning.
- Know when to use classification or regression methods.
- Use the metrics corresponding to the algorithms used.

## General analysis.

1. Conduct an analysis of the variables in the dataset, such as histograms, boxplots, etc. 
2. Treatment of missing values, outliers, missing values, etc. 
3. Removal of necessary variables.
4. Division of data into Train and Test.
5. Treatment of the categorical variables by converting them into numerical variables by means of dummies.
6. Normalisation of the data.
7. Implementation of: Logistic regression, K nearest neighbours, Decision tree.
8. Evaluation of each model.
