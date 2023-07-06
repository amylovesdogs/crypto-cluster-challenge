# crypto-cluster-challenge
## DU Data Analysis Module 19 Assignment, Unsupervised Learning
The challenge is to group cryptocurrencies based on their market price behavior at 1 day, 7 days, 14 days, 30 days, 60 days, 200 days and 1 year.

## The Approach
**Crypto_Clustering.ipynb** creates clusters based on the full original data and based on transformed data using Principal Component Analysis (PCA) with 3 components.

## The Result

Both methods show the the optimal number of clusters as 4. Both methods group the the cryptocurrencies into the same cluster groups, with ethlend and celsius-degree-token each in their own group due to their extreme 1-year and 200-day spikes. In short, the result of both analyses are the same.
