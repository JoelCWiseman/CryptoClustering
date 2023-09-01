# CryptoClustering

For this assignment I worked through the following steps which are outlined in the Ctypto_Clustering jupyter notebook in this respository. 
1) Prepare the Data
2) Find the Best Value for k Using the Original Scaled DataFrame
3) Cluster Cryptocurrencies with K-means Using the Original Scaled Data
4) Optimize Clusters with Principal Component Analysis
5) Find the Best Value for k Using the PCA Data
6) Cluster Cryptocurrencies with K-means Using the PCA Data

After completing the cleaning and coding there are 5 questions asked within the jupyter notebook.
1) Question: What is the best value for k?
   Answer: In this model, 4 is the best value for 'k'.

2) Question: What is the total explained variance of the three principal components?
   Answer: The total explained variance is the sum of the principal components, which is 0.88362409, which is alternatively written as 88.36%

3) Question: What is the best value for k when using the PCA data?
   Answer: When looking at the PCA model data, the bext value for 'k' is 5.

4) Question: Does it differ from the best k value found using the original data?
   Answer: Yes, the original data model, the best value for 'k' is 4.

5) Question: After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?
   Answer: The result in my data model are more spread out, and not a grouped together by using fewer features to cluster the data. By adding the additional features, it allows for the data to be structured in a way that the true grouping of the data reveals itself.
   
For this assignment, I relied on inclass examples, as well as my personal copy of Python for Data Analytics https://wesmckinney.com/book/
