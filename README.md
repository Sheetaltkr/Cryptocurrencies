# Cryptocurrencies

Use unsupervised machine learning techniques to analyze cryptocurrency data.

# Project Overview

## Purpose

- Analyze cryptocurrency dataset for preparing cryptocurrency investment portfolio for customers at Accountability Accounting using Unsupervised Machine Learning Data Model.
- Create a report including cryptocurrencies on the trading market and their possible groups to create a classification system for the new investment using clustering Algorithm
- Create data visualizations to share the findings with the board.

## Stages of Unsupervised Machine Learning process:
1. **Data preprocessing**. This step included in-depth data cleaning, such as removing null values and removing cryptocurrencies without coins mined. In addition, the encoding method "get_dummies()" was used for the text features and StandardScaler() was used to standardize and transform the data.
2. **Reducing data dimensions using PCA**. In this step, a dataframe's dimensions was reduced to three principal components and a new dataframe was created.
3. **Clustering cryptocurrencies using K-means**. During step, an elbow curve was created to find the best value for the clustering groups and a K-means algorithm was used to predict the K clusters for the cryptocurrencies’ data.
4. **Data Visualization**. In this final step, three types of figures were used: a 3D scatter plot to visualize the three PCAs, a hvplot.table to visualize all the current tradable cryptocurrencies, and a 2D scatter plot to visualize "Total Coins Mined" vs. "Total Coin Supply" by coin name and clusters.
