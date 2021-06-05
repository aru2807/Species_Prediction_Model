## Species_Prediction_Model

## INTRODUCTION:-

The Dataset consists of Sepal Length(Cm), Sepal Width(Cm), Petal Length(Cm), Petal Width(Cm) & Species. Here we have predicted the Species name though decisiontree classifier
and also visualize the decision tree.

## What is DecisionTreeClassifier ?

A Decision Tree is a simple representation for classifying examples. It is a Supervised Machine Learning where the data is continuously split according to a certain parameter.
Such a tree is built through a process known as binary recursive partitioning. This is an iterative process of splitting the data into partitions, and then splitting it up 
further on each of the branches.
Using the decision algorithm, we start at the tree root and split the data on the feature that results in the largest information gain (IG) (reduction in uncertainty towards 
the final decision).In an iterative process, we can then repeat this splitting procedure at each child node until the leaves are pure. This means that the samples at each leaf 
node all belong to the same class.In practice, we may set a limit on the depth of the tree to prevent overfitting. We compromise on purity here somewhat as the final leaves may 
still have some impurity.

## REQUIRED TO IMPORT:-

Here we import pandas, tree, DecisionTreeClassifier, sklearn, StringIO, export_graphviz, pydotplus & Image.

import pandas as pd

from sklearn import tree

from sklearn.tree import DecisionTreeClassifier
import sklearn.datasets as datasets
from sklearn.externals.six import StringIO
from sklearn.tree import export_graphviz
import pydotplus
from IPython.display import Image

## VISUALIZATION:-

For visualization I have drown the graph and crated a pdf and png.
