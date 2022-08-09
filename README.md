# KMeans_Clustering_Recommender_system

 **Introduction:**
            
This repo contains a code for a recommender system that works using KMeans clustering algorithm.
 
 **K-Means clustering**
 
K-Means Clustering is an Unsupervised Learning algorithm, which groups the unlabeled dataset into different clusters.
Here K defines the number of pre-defined clusters that need to be created in the process, as if K=2, there will be 
two clusters, and for K=3, there will be three clusters, and so on.

It allows us to cluster the data into different groups and a convenient way to discover the categories of groups in the unlabeled dataset on its own without the need for any training.

It is a centroid-based algorithm, where each cluster is associated with a centroid. The main aim of this algorithm is to minimize the sum of distances between the data point and their corresponding clusters.

The algorithm takes the unlabeled dataset as input, divides the dataset into k-number of clusters, and repeats the process until it does not find the best clusters. The value of k should be predetermined in this algorithm.

The k-means clustering algorithm mainly performs two tasks:

<ul>
<li>Determines the best value for K center points or centroids by an iterative process.</li>
<li>Assigns each data point to its closest k-center. Those data points which are near to the particular k-center, create a cluster.</li>
<li>Hence each cluster has datapoints with some commonalities, and it is away from other clusters.</li>
</ul>

 **About running the scripts**
 
 ✅ scraper.py to scrape imdb website
 
 ✅ pre-processing.py to preprocess the scraped data and store in desired format
 
 ✅ clustercode.py to prepare data and fit to kmeans clustering model from sklearn
 
 ✅ main.py to run the code in order no need to run pre process and clustercode they are imported by main and run automatically
 
 ✅ plot.py to plot the cluster results 
