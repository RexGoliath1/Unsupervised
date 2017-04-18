# Unsupervised

## General Preprocessing
http://scikit-learn.org/stable/modules/preprocessing.html
StandardScaler (Variance Scaling)
sklearn.pipeline.Pipeline
### Phil's Suggestion 
http://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html#sklearn.preprocessing.MinMaxScaler
MinMaxScaler in preprocessing
### Should I normalize my data?
http://www.faqs.org/faqs/ai-faq/neural-nets/part2/section-16.html
<br>sklearn.decomposition PCA/RandomizedPCA whiten=true to remove correlation across features
### Vector Space Model 
Scaling to unit norm: https://en.wikipedia.org/wiki/Vector_space_model
### Binarization
Thresholding numerical features to get boolean values
### Catagorical Encoding
OneHotEncoder (wut?)
http://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html#sklearn.preprocessing.OneHotEncoder

## PCA Visuals
Forked from : https://www.kaggle.com/tuomastik/santander-customer-satisfaction/pca-visualization/code

# Clustering
Number of Catagories Known
<br>Clustering Ideas:
<br>https://stats.stackexchange.com/questions/23472/how-to-decide-on-the-correct-number-of-clusters
<br>https://en.wikipedia.org/wiki/Dirichlet_process
## KMeans
## Spectral Clustering
Low Dimensional Embedding, then KMeans
<br>Efficient if Sparse Matrix. Works well with low number of clusters.
<br>Cuts are small compared to the weights of the edges inside each cluster.
## GMM

<br>Number of Clusters Unknown
## MeanShift
Computationaly Expensive
http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.76.8968&rep=rep1&type=pdf
## VBGMM

# Dimensionality Reduction
General Analysis
## Randomized PCA

## Kernel Approximation
Large Number of Samples
## Isomap
Small Number of Samples
## Spectral Embedding
## LLE

