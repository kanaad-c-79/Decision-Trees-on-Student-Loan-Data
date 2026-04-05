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
1) 
