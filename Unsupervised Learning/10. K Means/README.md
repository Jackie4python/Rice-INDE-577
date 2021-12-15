# K-Means Clustering
K-means clustering is one of the simplest and popular unsupervised machine learning algorithms. You’ll define a target number k, which refers to the number of centroids you need in the dataset. A centroid is the imaginary or real location representing the center of the cluster. Every data point is allocated to each of the clusters through reducing the in-cluster sum of squares. In other words, the K-means algorithm identifies k number of centroids, and then allocates every data point to the nearest cluster, while keeping the centroids as small as possible. The ‘means’ in the K-means refers to averaging of the data; that is, finding the centroid.

It uses an iterative technique to group unlabeled data into K clusters based on cluster centers (centroids). The data in each cluster are chosen such that their average distance to their respective centroid is minimized.

1.Randomly place K centroids for the initial clusters.  
2.Assign each data point to their nearest centroid.  
3.Update centroid locations based on the locations of the data points.  
4.Repeat Steps 2 and 3 until points don’t move between clusters and centroids stabilize.  

## Task
This project aims at analyzing the content of an E-commerce database that lists purchases made by  ∼ 4000 customers over a period of one year
(from 2010/12/01 to 2011/12/09). Based on this analysis, I develop a model that allows to anticipate the purchases that will be made by a new customer, 
during the following year and this, from its first purchase.

## Dataset
The data used for this model is a public data from Kaggle https://www.kaggle.com/fabiendaniel/customer-segmentation.
This file contains the basic information (ID, age, gender, income, spending score) about the customers.

## Libraires

Pandas https://pandas.pydata.org/  
Matplotlib https://matplotlib.org/  
Numpy https://numpy.org/  
Seaborn https://seaborn.pydata.org/  
Scikit-learn https://scikit-learn.org/  
Mlxtend http://rasbt.github.io/mlxtend/  
