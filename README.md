# CryptoClustering

This analysis uses Python and Unsupervised Learn to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

## Analysis Summary 

The majority of currencies fall into two groupings of being more impacted by the daily or weekly period. Both models had the same two outliers of celcius-degree-token and ethlend. 

## Method of Analysis 

1. Prepare the data using StandardScaler from scikit-learn

2. Find Best Value for k using the original scaled data frame

3. Cluster the cryptocurrencies based on k from scaled data

4. Analyze clusters through Principal Component Analysis (PCA) 

5. Find the best value for k using PCA data

6. Cluster the cryptocurrencies based on k from pca data

7. Create comparison for line elbow graphs - scaled and pca

8. Create comparison for scatter plot graphs - scaled and pca

