Customer Segmentation with K-Means Clustering

This readme file provides instructions for executing a Python script to perform customer segmentation using K-Means clustering. The script uses popular Python libraries, including NumPy, Pandas, Matplotlib, Seaborn, and Scikit-Learn.

 Prerequisites

Before executing the script, ensure you have the following prerequisites in place:
- Python installed on your system.
- Required libraries: NumPy, Pandas, Matplotlib, Seaborn, and Scikit-Learn (you can install them using pip).

 Script Description

This script performs the following tasks

1. Imports necessary libraries
  
2. Loads the customer data from a CSV file. Make sure to specify the correct file path
   
3. Displays the first few rows of the dataset

4. Gets information about the dataset
  
5. Checks for missing values in the dataset
  
6. Selects the features for clustering (Annual Income and Spending Score):
   
7. Determines the optimal number of clusters using the Elbow Method and plots the Elbow Point Graph to help choose the number of clusters
  
8. Initializes KMeans with the chosen number of clusters (e.g., 5)
   
9. Assigns each data point to a cluster and plots the data points and centroids for the clusters
   
Usage

To execute the script, follow these steps:

1. Ensure you have Python and the required libraries installed.
2. Specify the correct file path for the customer data CSV file.
3. Run the script.

The script will load the data, perform K-Means clustering, and display the results.
