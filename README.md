# Titanic-Data-Exploaration

**Titanic: Machine Learning from Disaster** 

**Start here! Predict survival on the Titanic and get familiar with ML basics**

**Website :** https://www.kaggle.com/c/titanic

![image](https://user-images.githubusercontent.com/31696557/48980382-2812bf00-f0ee-11e8-80fc-973bfcb34730.png)
Source: [National Geographic](https://www.nationalgeographic.org/thisday/apr15/titanic-sinks/)

This notebook is a simple example of titanic Disaster in python. It is a Kaggle Competition, [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic). It is good for those who are going into the field of Machine learning, Data Analysis or simple introduction to the Kaggle Prediction competition.

### Practice Skills

- Binary classification
- Python and R basics **[I'm choosing Python here..]**

## Evaluation

### Goal

It is your job to predict if a passenger survived the sinking of the Titanic or not. 
For each PassengerId in the test set, you must predict a 0 or 1 value for the Survived variable.

### Metric

Your score is the percentage of passengers you correctly predict. This is known simply as ["accuracy”](https://en.wikipedia.org/wiki/Accuracy_and_precision#In_binary_classification).

## Data Description

### Overview

The data has been split into two groups:

- training set (train.csv)
- test set (test.csv)

**The training set** should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use[feature engineering ](https://triangleinequality.wordpress.com/2013/09/08/basic-feature-engineering-with-the-titanic-data/)to create new features.

**The test set** should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

We also include **gender_submission.csv**, a set of predictions that assume all and only female passengers survive, as an example of what a submission file should look like.

### Data Dictionary

| **Variable** | **Definition**                             | **Key**                                        |
| ------------ | ------------------------------------------ | ---------------------------------------------- |
| survival     | Survival                                   | 0 = No, 1 = Yes                                |
| pclass       | Ticket class                               | 1 = 1st, 2 = 2nd, 3 = 3rd                      |
| sex          | Sex                                        |                                                |
| Age          | Age in years                               |                                                |
| sibsp        | # of siblings / spouses aboard the Titanic |                                                |
| parch        | # of parents / children aboard the Titanic |                                                |
| ticket       | Ticket number                              |                                                |
| fare         | Passenger fare                             |                                                |
| cabin        | Cabin number                               |                                                |
| embarked     | Port of Embarkation                        | C = Cherbourg, Q = Queenstown, S = Southampton |

### Variable Notes

**pclass**: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower
**age**: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5
**sibsp**: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)
**parch**: The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.





