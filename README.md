# Cryptocurrency

## Overview of Project
The purpose of this project is to analyze the portfolio assembled by Accountability Accounting, an investment bank, for cryptocurrencies using unsupervised learning. Additionally, they want the cryptocurrencies categorized in a way to help indicate what trading market it is in.

## Process
1. Cleaning the data - data was imported into a Jupyter Notebook and transformed into a DataFrame, where columns were analyzed for their usefulness and null or NaN values. Some columns and rows were filtered or removed to better utilize the data
2. Principal Component Analysis - compartmentalizes our data and limits the dimensions of our data so that it is more usable
3. Clustering Cryptocurrencies - first, creating an elbow curve to determine the most likely number of categories that the cryptocurrencies can fall under (decision is k=4), then running that through the K-means model to predict the categories each of our data points falls under.
4. Visualizing the Cryptocurrency data - Graph on a 2D and 3D scatter plot to visualize the clusters and their differences
