# Clustering-Customer-Segmentation-Project

In this project, customers are required to be segmented according to the purchasing history obtained from the membership cards of a big mall.

After getting to know the data set, I performed Exploratory Data Analysis. I observed the distribution of customers according to different variables, also discovered relationships and correlations between variables. Then I spesified the different variables to use for cluster analysis.

Finally, I clustered customers using the K-Means Clustering method and Hierarchical Clustering method, after that label the clusters. 

For K-Means Clustering; firstly, I clustered based on "Age" and "Spending Score". I used elbow method, Yellowbrick Visualizer and Silhouette Score methods in order to determine cluster number and found k number is equal to 4. Then I applied K-Means Clustering with k=4 and visualized the results. Then, I tried to clustered based on "Annual Income" and "Spending Score". Again, I applied three methods which are Elbow method, Yellowbrick Visualizer and Silhouette Score to find out the k number. This time I found k = 5 and applied K-Means Clustering with k=5 and visualized the results. Clustering with k=5 is better than the other and I got more clear clusters.

For Hierarchical Clustering; firstly, I clustered based on "Age" and "Spending Score". I used Dendrogram Diagrams and Silhouette Score methods to find out k number. K equals to 4 based on those variables and I applied Agglomerative Clustering with k=4 and visualised the results. Then, I tried to clustered based on "Annual Income" and "Spending Score". Again, I applied both methods; Dendrogram Diagrams and Silhouette Score methods in order to find k number. This time I found k = 5 applied Agglomerative Clustering with k=5 and visualised the results. Clustering with k=5 is better than the other and I got more clear clusters.

# Tasks

#### 1. Import Libraries, Load Dataset, Exploring Data
- Import Libraries
- Load Dataset
- Explore Data

#### 2. Exploratory Data Analysis (EDA)


#### 3. Cluster Analysis

- Clustering based on Age and Spending Score

    *i. Create a new dataset with two variables of your choice*
    
    *ii. Determine optimal number of clusters*
    
    *iii. Apply K Means*
    
    *iv. Visualizing and Labeling All the Clusters*
    
    
- Clustering based on Annual Income and Spending Score

    *i. Create a new dataset with two variables of your choice*
    
    *ii. Determine optimal number of clusters*
    
    *iii. Apply K Means*
    
    *iv. Visualizing and Labeling All the Clusters*
    
    
- Hierarchical Clustering

    *i. Determine optimal number of clusters using Dendogram*

    *ii. Apply Agglomerative Clustering*

    *iii. Visualizing and Labeling All the Clusters* 

- Conclusion
