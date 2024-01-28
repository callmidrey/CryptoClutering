# CryptoClustering
This is my Module 19 Challenge
This challenge was a little legnthy than usual but I gave it my best shot.

# Background
THus project employed the knowledgge of Python and unsupervised learnign to make predictions of cryptocurrencies if they wew affected by 24-hour or 7-day price changes. The project was conducted using pythom language in Jupyternotebook.

# Process:
The project went through some steps:
1- Preparing the data
2- Finding the Best Value for k Using the Original Scaled DataFrame
3- Clustering Cryptocurrencies with K-means Using the Original Scaled Data
4- Optimizing Clusters with Principal Component Analysis
5- Finding the Best Value for k Using the PCA Data
6- Clustering Cryptocurrencies with K-means Using the PCA Data

# Results
The process that was followed above was in quest to answer the following questions in order of the steps above:
1. Question: What is the best value for `k`?
    *Answer:  The best value for K from the graph suggests 4.*

2. Question: What is the impact of using fewer features to cluster the data using K-Means?
    *Answer: Reducing the number of features for K-Means clustering simplifies the dataset, potentially improving algorithm performance and      interpretability. It lead to faster computations and more robust clusters, but also resulted in information loss. Balancing simplicity and information retention is crucial for effective clustering analysis.*

3. Question: What is the total explained variance of the three principal components?
    *Answer: Approximately 89.5% or 0.895.*

4. Question: What is the best value for `k` when using the PCA data?
    *Answer: From the graph generated, it suggest  the best k value is 4.*

5. Question: Does it differ from the best k value found using the original data?
    *Answer: There is not a difference in K value when using the orignal data and the PCA data. It is the same.*

6. Question: After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?
    *Answer: Using fewer features for K-Means clustering enhances the clarity of cluster boundaries and improves result interpretation. It leads to less overlap among clusters and clearer identification of the optimal cluster count through a more pronounced "elbow" point in the inertia plot. Despite the reduced feature set, the clustering process effectively captures the data's fundamental characteristics and structure. Overall, employing fewer features enhances the effectiveness of K-Means clustering analysis.*


