## CryptoClustering Project
Uncover insights into the cryptocurrency market using Python and unsupervised learning techniques. This project dives into predicting the influence of 24-hour and 7-day price changes on cryptocurrencies through clustering analysis

## 1. Data Preparation
Normalize data with StandardScaler().
Create a DataFrame with scaled data, setting "coin_id" as the index.
## 2. Find Optimal k Value Using Original Scaled Data
Implement the elbow method.
Visualize inertia values.
Determine the best value for k.

![Screenshot 2024-01-14 at 5 42 15 PM](https://github.com/mervecelme/CryptoClustering/assets/140986062/ac3dc4ab-f9e7-4e76-b02f-3b0fa3745198)



## 3. Cluster Cryptocurrencies with K-means Using Original Scaled Data
Initialize K-means model with the optimal k value.
Fit the model using the original scaled DataFrame.
Predict clusters and add a new column.
Visualize clusters with a scatter plot using hvPlot.

![Screenshot 2024-01-14 at 5 42 42 PM](https://github.com/mervecelme/CryptoClustering/assets/140986062/8d1b14c3-8541-4428-aa28-80212f977769)



## 4. Optimize Clusters with Principal Component Analysis (PCA)
Perform PCA on the original scaled DataFrame.
Retrieve explained variance.
## 5. Find Optimal k Value Using the PCA Data
Implement elbow method on PCA data.
Visualize inertia values.

![Screenshot 2024-01-14 at 5 43 13 PM](https://github.com/mervecelme/CryptoClustering/assets/140986062/5a3a4499-d619-492b-bd76-9ef895656af6)



## 6. Cluster Cryptocurrencies with K-means Using the PCA Data
Initialize K-means model with the optimal k value.
Fit the model using PCA data.
Predict clusters and add a new column.
Visualize clusters with a scatter plot using hvPlot.


![Screenshot 2024-01-14 at 5 43 41 PM](https://github.com/mervecelme/CryptoClustering/assets/140986062/a309981f-0207-4e50-a762-651566065055)

## References
https://medium.com/analytics-vidhya/how-to-determine-the-optimal-k-for-k-means-708505d204eb
https://medium.com/analytics-vidhya/choosing-the-best-k-value-for-k-means-clustering-d8b4616f8b86
