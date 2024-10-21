# CryptoClustering

In this project I look at the best way to cluster the crypto coin data using KMeans on the original scaled data and using Principal Component Analysis.

Run the Crypto_Clustering_starter_code.ipynb file in the Starter_Code folder to begin.

First the data is scaled and inertia is calculated to find the best value for k using the original scaled data.
The best value for k according to the elbow plot was 4.

Next using PCA data, and calculating inertia again, the best value for k was once again 4.

Then the weights of the features were calculated to show which features had the most influence on each component. 
 In PCA1, price_change_percentage_200d has the most influence at 0.594468. In PCA2, price_change_percentage_30d has the most influence at 0.562182. In PCA3, price_change_percentage_7d has the most influence at 0.787670
