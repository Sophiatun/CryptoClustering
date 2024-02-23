# CryptoClustering

Used the elbow curve method to normalized data and to find the optimal k value for the K-Means model that will use all of the original features of the dataset.

![K Value](https://github.com/Sophiatun/CryptoClustering/blob/main/Resources/Images/k_value.png)https://github.com/Sophiatun/CryptoClustering/blob/main/Resources/Images/k_value.png)


Then, using the optimal k value I train and predict the K-Means model to generate 4 clusters of cryptocurrencies. The inertia of each cluster was significant enough to consider reducing the amount of features.
![Clusters](https://github.com/Sophiatun/CryptoClustering/blob/main/Resources/Images/clusters.png)


After that, used the PCA data to again calculate the optimal k value for the K-Means model.
![PCA Prediction](https://github.com/Sophiatun/CryptoClustering/blob/main/Resources/Images/pca_prediction.png)


Lastlt, with the optimal k value for the PCA features,plot to get the new clusters.
![K means](https://github.com/Sophiatun/CryptoClustering/blob/main/Resources/Images/kmeans.png)

