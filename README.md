# Principles of Data Analytics

by Marcin Kaminski

## Setup

1. Sign up for a free GitHub account.
2. Go to the repository page in your browser.
3. Click the green Code button.
4. Click the Codespaces tab.
5. Click Create New Codespace on main.

## Technologies

- Python
- Git
- GitHub
- Codespaces
- Jupyter

# Iris Dataset Analysis

This notebook provides a comprehensive analysis of the Iris dataset, covering data loading, exploration, visualization, and statistical summaries. The Iris dataset is a classic dataset in machine learning and statistics, containing measurements of three iris species: setosa, versicolor, and virginica.

## Table of Contents
1. [Task 1: Source the Data Set](#Task-1)
2. [Task 2: Explore the Data Structure](#Task-2)
3. [Task 3: Summarize the Data](#Task-3)
4. [Task 4: Visualize Features](#Task-4)
5. [Task 5: Investigate Relationships](#Task-5)
6. [Task 6: Analyze Relationship](#Task-6)
7. [Task 7: Analyze Class Distributions](#Task-7)
8. [Task 8: Compute Correlations](#Task-8)
9. [Task 9: Fit a Simple Linear Regression](#Task-9)
10. [Task 10: Too Many Features ](#Task-10)

##Task-1
Import the Iris data set from the `sklearn.datasets` module.  
Explain, in your own words, what the `load_iris()` function returns.

##Task-2
Print and explain the shape of the data set, the first and last 5 rows of the data, the feature names, and the target classes. 

##Task-3
For each feature in the dataset, calculate and display:  
- mean
- minimum
- maximum
- standard deviation
- median

##Task-4
Plot histograms for each feature using `matplotlib`.  
Add appropriate titles and axis labels.  

##Task-5
Choose any two features from the data set and create a scatter plot of them.  
Color-code the three different classes of the scatter plot points.

##Task-6
Use `numpy.polyfit` to add a regression line to the scatter plot from Task 5.

##Task-7
Create box-plots of the petal lengths for each of the three classes.

##Task-8
Calculate the correlation coefficients between the features.  
Display the results as a heatmap using `matplotlib`. 

##Task-9
For your two features in Task 5, calculate the coefficient of determination $R^2$.  
Re-create the plot from Task 6 and annotate it with the $R^2$ value.

##Task-10
Use `seaborn` to create a `pairplot` of the data set.  
Explain, in your own words, what the `pairplot` depicts.
