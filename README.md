## Predicting Heart disease using Machine Learning
 
This notebook looks into using various Python based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes.

### What is classification?
Supervised learning is a process of providing input data as well as correct output data to the machine learning model. The aim of a supervised learning algorithm is to find a mapping function to map the input variable(x) with the output variable(y).

**Classification** is one such type of Supervised Learning technique that is used to identify the **category of new observations** on the basis of training data. In Classification, a program learns from the given dataset or observations and then classifies new observation into a **number of classes or groups**.

I have going to follow the life-cycle of a machine learning problem and take the following approach to tackle the problem:
- **Problem Definition** - What problem am I trying to solve?
- **Data** - What data do I have?
- **Evaluation** - What defines success?
- **Features** - What features should I model?
- **Modelling** - What kind of model should I use?
- **Experimentation** - What have I tried/ what else can I try?

### Problem Definition

In a statement,

> Given clinical parameters about a patient, can we predict whether or not they have heart disease?

### Data

The original data came from Cleavland database from the UCI Machine Learning repository:https://archive.ics.uci.edu/ml/datasets/heart+Disease

There is also a version of it available on Kaggle: https://www.kaggle.com/ronitf/heart-disease-uci

The original database contains **76 attributes**, but here only **14 attributes** will be used. Attributes (also called **features**) are the variables what we'll use to predict our target variable.




