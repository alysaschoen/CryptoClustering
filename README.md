# CryptoClustering

![Cryptocurrency](https://www.usatoday.com/money/blueprint/images/uploads/2023/03/01013406/what-is-cryptocurrency-e1690868078577.jpg?width=700&fit=cover&format=webp)

## Objective
Utilize Python and unsupervised learning techniques to forecast the impact of 24-hour or 7-day price fluctuations on cryptocurrencies.

## Execution
1. Data Preparation: <br>
*Ensure data is properly formatted and scaled for analysis.*

2. Determine Optimal k Value Using Original Scaled Data: <br>
*Employ methods to find the most suitable k value for K-means clustering with the initial scaled dataset.*

3. Conduct K-means Clustering on Cryptocurrencies Using Original Scaled Data: <br>
*Apply the K-means algorithm to cluster cryptocurrencies based on the identified optimal k value.*

4. Refine Clusters with Principal Component Analysis (PCA): <br>
*Utilize PCA to enhance cluster analysis and refine the grouping of cryptocurrencies.*

5. Identify Optimal k Value Using PCA-transformed Data: <br>
*Explore PCA-transformed data to determine the optimal k value for an improved clustering approach.*

6. Perform K-means Clustering on Cryptocurrencies Using PCA-transformed Data: <br>
*Execute K-means clustering on cryptocurrencies using the PCA-transformed features for a more insightful and refined clustering outcome.*

## Questions & Answers

1. What is the best value for `k`?  <br> <br>
  **Four** <br> <br>
   
2. What is the total explained variance of the three principal components?  <br> <br>
  **89.5%** <br> <br>

3. What is the best value for k when using the PCA data?  <br> <br>
  **Four** <br> <br>
  
4. Does it differ from the best k value found using the original data?  <br> <br>
  **It aligns with the optimal k value identified in the original dataset; both cases identify four as the best k value.** <br> <br>
  
5. After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?  <br> <br>
   **After inspecting the results of the cluster analysis, opting for fewer features, specifically two clusters in this instance, results in a more concise grouping of the data.**


 <br>
  <br>
   <br>



