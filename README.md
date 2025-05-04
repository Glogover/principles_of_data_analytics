# Iris Dataset Analysis

by Marcin Kaminski

This notebook provides a comprehensive analysis of the Iris dataset, covering data loading, exploration, visualization, and statistical summaries. The Iris dataset is a classic dataset in machine learning and statistics, containing measurements of three iris species: setosa, versicolor, and virginica.

## Technologies

- Python
- Git
- GitHub
- Codespaces
- Jupyter

## Libraries

- Pandas
- Scikit-learn
- NumPy
- Pyplot
- Seaborn 
- SciPy

## Table of Contents

1. [Task 1: Source the Data Set]

    Import the Iris data set from the `sklearn.datasets` module.  
    Explain, in your own words, what the `load_iris()` function returns.

2. [Task 2: Explore the Data Structure]

    Print and explain the shape of the data set, the first and last 5 rows of the data, the feature names, and the target classes. 

3. [Task 3: Summarize the Data]

    For each feature in the dataset, calculate and display:  
    - mean
    - minimum
    - maximum
    - standard deviation
    - median

4. [Task 4: Visualize Features]

    Plot histograms for each feature using `matplotlib`.  
    Add appropriate titles and axis labels.  

5. [Task 5: Investigate Relationships]

    Choose any two features from the data set and create a scatter plot of them.  
    Color-code the three different classes of the scatter plot points.

6. [Task 6: Analyze Relationship]

    Use `numpy.polyfit` to add a regression line to the scatter plot from Task 5.

7. [Task 7: Analyze Class Distributions]

    Create box-plots of the petal lengths for each of the three classes.

8. [Task 8: Compute Correlations]

    Calculate the correlation coefficients between the features.  
    Display the results as a heatmap using `matplotlib`. 

9. [Task 9: Fit a Simple Linear Regression]

    For your two features in Task 5, calculate the coefficient of determination $R^2$.  
    Re-create the plot from Task 6 and annotate it with the $R^2$ value.

10. [Task 10: Too Many Features ]

    Use `seaborn` to create a `pairplot` of the data set.  
    Explain, in your own words, what the `pairplot` depicts.
