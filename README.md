# Decision-Trees-on-Student-Loan-Data
# Description
The 'DecisionTreeClassifier()' function is part of the 'tree' module of ScikitLearn.

The basic idea behind this algorithm for classification via decision trees:

1) Load the dataset.
2) Select the best arrtribute - using Attribute Selection Measures (ASM) - to split the records.
3) Make this best attribute a decision node - and break the dataset into smaller subsets.
4) Start building the tree - by repeating this process recursively for each child - until one of these conditions will match:
a) There are no more instances/tuples; b) There are no more remaining attributes; c) All the tuples/instances belong to the same attribute value.

# Predict Defaults for Student Loans applications
We used a Student Loan dataset to Predict Defaults for student loan Applications using regression trees - performing the following steps:

1) Loaded the dataset into Python and performed Exploratory Data Analysis.
2) Translated the categorical predictors into numerical predictors.
3) Shuffled the dataset - and then split it into 50% training data, 25% validation data, and 25% test data.
4) Calculated the accuracy of the Naïve benchmark on the training and validation datasets.
5) Trained a decision tree - using the default settings.
6) Re-tried the previous step (training the decision tree) - using different maximum depths for the tree.
7) Chose the appropriate tree depth and justified the choice. -> Re-trained the best classifier using all the samples - from both the training and the validation set. -> Retrained the best classifier on all the samples (including the test set) - and described the tree that we obtained.

The dataset has the following fields regarding students: field of study, graduation year, loan amount, gender, whether they've defaulted.

The naïve benchmark is a baseline model, which has no real learning/hasn't really learned anything yet from your data.

In this type of classification problem (very likely predicting something like default/no default), the naïve approach is - always predict the most common class in the dataset. 

Example: If 70% of students do not default and 30% do default, then the naïve model simply predicts 'no default' for every single case. The naïve accuracy in this case would be 0.70/70%.

The naïve benchmark tells you the minimum performance your real model must beat. It acts as a reference point for whether your model is actually learning anything meaningful. 

......................................

......................................

......................................




