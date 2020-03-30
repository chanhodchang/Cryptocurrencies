# Cryptocurrencies
Using unsupervised machine learning to analyze cryptocurrency data.

## Project Overview
Extracted, transformed, and loaded cryptocurrency data to use for analysis. Used unsupervised machine learning to create PCA and clusters. These were then used to create 2d and 3d diagrams to visualize the cryptocurrecny data.

## Resources
- Data Sources: crypto_data.csv
- Software: Python 3.8.2, Pandas 1.0.1, Scikit-learn 0.22, Plotly 4.5.4, hvPlot 0.5.2

## Analysis
The cryptocurrency data first under went to the ETL process to clean the data and prepare it for use in machine learning. Then the data was split into 3 different principal components.
The variance ratio came out to 0.0217, 0.0201, 0.0193.
An elbow curve was then created to see what the best value for the K.
The strongest cureve on the Elbow Curve fell at 4, so there were 4 different clusters created.
Form there the model.fit was used to classify each data values into a specific cluster.
Most of the cryptocurriencies fell under cluster 0 or 2.
These two cluster are also very close in proximity with 3 also being close by while there was only one value for cluster 1 and it is an outlier to the rest of the data points.
A MinMax scatterplot was then created to determine which Coin was  mined and supplied the most.
The plot shows that cluster 0 and 2 are the more popular coins that are being mined and supplied currently. 