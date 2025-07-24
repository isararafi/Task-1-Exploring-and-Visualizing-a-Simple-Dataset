# Task 1: Exploring and Visualizing the Iris Dataset

## Objective
The goal of this task is to learn how to load, inspect, and visualize a simple dataset using Python.  
It focuses on understanding data trends, distributions, and detecting potential outliers through basic data exploration and plotting.

## Dataset Used
- **Name:** Iris Dataset
- **Source:** Loaded directly using the Seaborn library
- **Description:** A classic dataset that contains 150 samples of iris flowers with four features:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
  - Species (Setosa, Versicolor, Virginica)

## Models Applied
- No machine learning models were applied in this task.
- The task focused on:
  - Data loading and inspection with **pandas**
  - Descriptive statistics (`.info()`, `.describe()`)
  - Visualization using **matplotlib** and **seaborn**:
    - Scatter plots to show relationships between features
    - Histograms to display value distributions
    - Box plots to identify outliers

## Key Results and Findings
- The scatter plot showed clear clusters for different species, especially between petal and sepal dimensions.
- Histograms revealed the distribution of each feature, highlighting how petal length and width differ significantly between species.
- Box plots helped identify potential outliers, especially in petal length and width.
- Overall, the Iris dataset is well-structured with clear separability among species, making it suitable for basic classification tasks.

