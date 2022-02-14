# Module 10 Challenge

UNCC Online FinTech Bootcamp Module 10

-----

## Executive Summary

As an advisor of a top five financial advisory firm in the world, I have proposed a novel approach to assembling investment portfolios that are based on cryptocurrencies. The goal of this project is to create a Jupyter notebook that clusters cryptocurrencies by their performance in different time periods. The results will be plotted so as to visually show the performance to the board.

-----

## Technologies / Installation Guide

This application is written in Python 3.7 using JupyterLab version 3.0.14.

Import the following libraries:

- import pandas as pd (*an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.*)
- import hvplot.pandas (*a high-level plotting API for the PyData ecosystem built on HoloViews.*)
- from path import Path (*a library that enables consistent input and output of files from the main app.*)
- from sklearn.cluster import KMeans (*a library that enables an unsupervised machine learning technique to identify clusters of data objects in a dataset.*)
- from sklearn.decomposition import PCA (*a library that enables a statistical technique to convert high dimensional data to low dimensional data by selecting the most important features that capture maximum information about the dataset.*)
- from sklearn.preprocessing import StandardScaler (*a library that allows for the distribution of values so that the mean of observed values is 0 and the standard deviation is 1.*)

-----

## Usage

The `crypto_investments.ipynb` notebook will be used to complete the following tasks:

- Find the Best Value for k Using the Original Data
- Cluster Cryptocurrencies with K-means Using the Original Data
- Optimize Clusters with Principal Component Analysis
- Find the Best Value for k Using the PCA Data
- Cluster Cryptocurrencies with K-means Using the PCA Data
- Visualize and Compare the Results

-----

## Visualizations

### Elbow Curve Plot

<img width="712" alt="elbow_curve" src="https://user-images.githubusercontent.com/94569323/153799713-0eebb2b2-9476-4ecb-91a7-6e420ebbb986.png">

### Cluster Plot

<img width="713" alt="cluster_plot" src="https://user-images.githubusercontent.com/94569323/153799729-2bd0d202-bfe5-4b7c-a4c5-991338ece16d.png">

### PCA Elbow Curve Plot

<img width="725" alt="pca_elbow" src="https://user-images.githubusercontent.com/94569323/153799739-d869e099-26d9-47bf-8dc2-713b026d551a.png">

### PCA Cluster Plot

<img width="718" alt="pca_cluster" src="https://user-images.githubusercontent.com/94569323/153799755-19e1a6f2-0375-498b-afaf-8a4bbb9e3cb2.png">

-----

## Results

- The first principal component contains 38.93% of the variance, the second principal component contains 29.16% of the variance, and the third pricipal component contains 20.81% of the variance. Thus, the three components contain 88.9% of the original information.
- According to the plots, the best k value found using the original data and the best k value found using the PCA data are both equal to 4.
- The PCA Cluster Plot is easier to visualize than the original Cluster Plot because we now have only two features. The first feature, or principal component, (PC1) runs along the x-axis, and the second feature (PC2) runs along the y-axis.

-----

## Contributors

Chancie Altham

-----

## License

MIT License