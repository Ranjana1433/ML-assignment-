# Dataset Exploration: Iris Dataset

## Overview

This project demonstrates how to load, explore, and analyze the famous *Iris dataset* using Python's sklearn and pandas libraries. The Iris dataset is a popular dataset in machine learning and statistics, containing 150 samples of iris flowers from three different species (setosa, versicolor, virginica), with four features (sepal length, sepal width, petal length, petal width) that describe each flower. The goal of this project is to perform some basic data exploration techniques to understand the dataset.


pip install numpy pandas scikit-learn


## Steps

1. *Load the Iris dataset*: 
   - The Iris dataset is included in the sklearn.datasets module and can be easily loaded using the load_iris() function.
   
2. *Display the first five rows of the dataset*: 
   - After loading the data into a pandas DataFrame, the first five rows will be displayed using the head() method.

3. *Display the dataset’s shape*: 
   - The shape of the dataset (i.e., the number of rows and columns) will be printed using the shape attribute.

4. *Summary statistics*: 
   - Calculate and display summary statistics such as the mean, standard deviation, minimum, maximum, and other descriptive statistics for each feature in the dataset using the describe() method.

## Code Example

python

Import necessary libraries

import pandas as pd

import numpy as np

from sklearn.datasets import load_iris

Load the Iris dataset

iris = load_iris()

# Create a DataFrame from the dataset
df = pd.DataFrame(data=iris['data'], columns=iris['feature_names'])

# Display the first five rows of the dataset
print("First five rows of the Iris dataset:")

print(df.head())

# Display the shape of the dataset
print("\nShape of the dataset (rows, columns):")

print(df.shape)

# Display summary statistics for the dataset
print("\nSummary statistics for the Iris dataset:")

print(df.describe())


## Expected Output

1. *First Five Rows*:
   The first five rows of the dataset will display the features for each iris sample (sepal length, sepal width, petal length, petal width).

2. *Dataset Shape*:
   The output will show the shape of the dataset, which should be (150, 4) indicating 150 samples and 4 features.

3. *Summary Statistics*:
   The summary statistics will display the mean, standard deviation, minimum, maximum, and percentiles for each feature. For example:




## Conclusion

This exploration of the Iris dataset provides a basic understanding of the dataset's structure and statistical properties. This step-by-step analysis is helpful for those starting out in data exploration and machine learning, laying the groundwork for more advanced techniques such as visualization, feature engineering, and modeling.
