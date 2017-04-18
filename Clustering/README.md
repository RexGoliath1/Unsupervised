# Choosing the number of clusters

# Bayesian Information Criterion (BIC)
Log-Likelihood of the dataset X according to model C, depending on the p parameters , and n datapoints.
<br>X-Means: Efficient Estimation of Clusters
http://www.aladdin.cs.cmu.edu/papers/pdfs/y2000/xmeans.pdf

Learning K in K Means:
http://papers.nips.cc/paper/2526-learning-the-k-in-k-means.pdf
BIC does not penalize model complexity strongly enough. (1 -> K Splits until points assigned to each reach Gaussian Distribution)

## Elbow Method
https://en.wikipedia.org/wiki/Determining_the_number_of_clusters_in_a_data_set

## Silhouette Analysis
http://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_silhouette_analysis.html

## Other Methods 
Class ClusterScore:
https://en.wikipedia.org/wiki/Determining_the_number_of_clusters_in_a_data_set
Minimum Spanning Tree: 
https://en.wikipedia.org/wiki/Minimum_spanning_tree
https://en.wikipedia.org/wiki/Single-linkage_clustering

Matlab:
evalclusters: 
<br>3 clustering algorithms: Kmeans, Linkage, and gdistribution
<br>4 clustering evaluation criteria: CalinskiHarabasz, DaviesBouldin, gap, silhouette

## Rule of Thumb
Number of Clusters: k = (n/2)^0.5
G-Means: Distribution is Gaussian, increase k until your groups follow Gaussian Distro.
(Explained in 'Learning the K in K Means')

Good Silhouette Analysis:
https://stats.stackexchange.com/questions/10540/how-to-interpret-mean-of-silhouette-plot

Meta Heuristic Algorithm (GA) to find k wrt. Silhouette

Cluster Iteration:
http://stackoverflow.com/questions/1793532/how-do-i-determine-k-when-using-k-means-clustering

Starting Point was here: (Great Suggestions)
https://stats.stackexchange.com/questions/23472/how-to-decide-on-the-correct-number-of-clusters
