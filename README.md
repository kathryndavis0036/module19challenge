# module19challenge
This project performs clustering analysis on cryptocurrency data using K-Means clustering. The analysis includes data preprocessing, clustering with K-Means, and visualizing results using PCA (Principal Component Analysis) and scatter plots.

# Project Overview
- Data Loading: Load cryptocurrency market data from a CSV file.

  # Data Preprocessing:
- Normalize the data using StandardScaler.
- Perform PCA to reduce dimensionality.
  # K-Means Clustering:
- Determine the optimal number of clusters using the elbow method.
- Apply K-Means clustering to both the original and PCA-transformed data.
  # Visualization:
- Create scatter plots to visualize clustering results.
- Compare clustering results between original and PCA data.

  # Requirements
- pandas
- hvplot
- matplotlib
- scikit-learn

  # Usage
Load and Prepare Data: Update the path to your data file in the script.

Run the Analysis: Execute the script to perform clustering and generate plots.

View Results: Check the scatter plots and elbow curves to interpret the clustering results.

  # Files
crypto_market_data.csv: Input data file.

clustering_analysis.py: Script for data analysis and visualization.
