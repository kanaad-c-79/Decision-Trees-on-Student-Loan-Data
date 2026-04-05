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

The dataset has the following fields regarding students: field of study, graduation year, loan amount, gender, whether they've defaulted.
2) Translated the categorical predictors into numerical predictors.
3) Shuffled the dataset - splitting it into 50% training data, 25% validation data, and 25% test data.
4) Calculated the accuracy of the Naïve benchmark on the validation set.
5) Trained a decision tree - using the default settings.
6) Re-tried the previous step (training the decision tree) - using different maximum depths for the tree.
7) Chose the appropriate tree depth and justified the choice. -> Re-trained the best classifier using all the samples - from both the training and the validation set. -> Retrained the best classifier on all the samples (including the test set) - and described the tree that we obtained.


