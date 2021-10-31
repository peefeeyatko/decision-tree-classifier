# Decision Tree Classifier

The problem this Decision Tree algorithm solves involves predicting whether a banknote is authentic or not.

The dataset provides a number of samples of banknotes and their measurements taken from a very detailed photograph.

Each data sample is categorized into one of two classifications: 1 (authentic) or 0 (inauthentic), making this a binary classification problem.

### Implementation

The raw Banknote Authentication dataset is included into the notebook from a remote CSV file.

The dataset is then partitioned into a training set for building the model and a testing set to make predicitons and provide an accuracy score.

### CART Algorithm

The tree is built recursively while calculating the information gain and gini impurity at each node to provide the best possible split.

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/peefeeyatko/decision-tree-classifier/blob/main/31005_A2_Marshall_Sutton_13583378.ipynb)