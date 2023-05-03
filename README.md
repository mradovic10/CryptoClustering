# CryptoClustering
Module 19 Challenge

For this challenge, I utilized my knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

The data used is found in the Resources folder, titled "crypto_market_data".

First, StandardScaler from scikit-learn was used to normalize the data and make it easier to compare and contrast. Then, I used the Elbow method to find the best value for 'k'. Once found, I initialized the KMeans model using the best value (4) and created a scatter plot to depict the data given the predicted cluster groups.

After that, I optimized the cluster groups using PCA (Principal Component Analysis). The features were reduced to three main components, which would make it clearer to see the distinction between each cluster group.

As in the first part of the analysis using the original scaled data, I used the elbow method to find the best value for 'k'. Then, the cryptocurrencies were again clustered, this time using the PCA data.

Finally, I was able to visualize and compare the results of both methods to see the impact of using fewer features to cluster the data using KMeans.

The 'crypto_clustering' Jupyter Notebook is thoroughly commented with relevant notes explaining the code and analysis.


MR