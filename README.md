# CryptoClustering - Module 19 Challenge

In this challenge, Python knowledge and unsupervised learning are used to predict whether cryptocurrencies are affected by 24-hour or 7-day price changes.


You will find a jupyter file ( Crypto_Clustering ) with the following main steps developed:
## Prepare the Data
*  Using the StandardScaler() module from scikit-learn to normalize the data from the CSV file.
## Find the Best Value for k Using the Original Scaled DataFrame
* Using the elbow method to find the best value for k 
## Cluster Cryptocurrencies with K-means Using the Original Scaled Data
## Optimize Clusters with Principal Component Analysis
*  Using the original scaled DataFrame, perform a PCA and reduce the features to three principal components
## Find the Best Value for k Using the PCA Data
*  Using  the elbow method on the PCA data to find the best value for k.
## Cluster Cryptocurrencies with K-means Using the PCA Data
*  Using the following steps to cluster the cryptocurrencies for the best value for k on the PCA data
## Visualize and Compare the Results
* Using hvplot and hv.extension('bokeh')
