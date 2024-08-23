# K-means-Clustering-with-Python
This repository contains code for K-Means Clustering in Python, based on the work from the following Kaggle notebook: [K-Means Clustering with Python by prashant111](https://www.kaggle.com/code/prashant111/k-means-clustering-with-python/notebook).

# Dataset Overview
Facebook pages of 10 Thai fashion and cosmetics retail sellers. Posts of a different nature (video, photos, statuses, and links). Engagement metrics consist of comments, shares, and reactions.

[https://archive.ics.uci.edu/dataset/488/facebook+live+sellers+in+thailand]

# Dataset Information

## Variables Table

| Variable Name      | Role      | Type         | Description | Units | Missing Values |
|--------------------|-----------|--------------|-------------|-------|----------------|
| status_id          | ID        | Integer      |             |       | No             |
| status_type        | Feature   | Categorical  |             |       | No             |
| status_published   | Feature   | Categorical  |             |       | No             |
| num_reactions      | Feature   | Integer      |             |       | No             |
| num_comments       | Feature   | Integer      |             |       | No             |
| num_shares         | Feature   | Binary       |             |       | No             |
| num_likes          | Feature   | Integer      |             |       | No             |
| num_loves          | Feature   | Binary       |             |       | No             |
| num_wows           | Feature   | Binary       |             |       | No             |
| num_hahas          | Feature   | Binary       |             |       | No             |
| num_sads           | Feature   | Binary       |             |       | No             |
| num_angrys         | Feature   | Binary       |             |       | No             |


# Result and Conclusion
- In this project I have implemented Kmeans Clustering.
- Use minmax and Standard scale to normalize data and choose minmax for nomralization because clustering result were better through that
- Use Elbow method to find the best number of cluster in Kmeans
- Based on elbow method number of clusteres equals 2 is the best value.
- Analyse the result of Kmeans Clusetring with silhouette method.
- Based on Silhoute method average score equals 0.88
- Analyse clustering by grouping clusters based on cluster's label
- make a visual consideration over Kmeans Clustering with pair plot and scatter plot. 
