# Introduction

Data clustering involves grouping data points or objects based on their similarity or distance from each other. 
It is a fundamental unsupervised learning technique in machine learning and data mining that can be applied to various fields, such as image processing,
natural language processing, customer segmentation, and anomaly detection.

## Encoding Categorical variables

One important aspect of clustering is data encoding, which refers to the process of transforming raw data into a more suitable format for clustering algorithms.
Common encoding techniques include one-hot encoding and  Label encoder for categorical data.

## Clustering techniques in python

* k-means algorithm -it is implemented in Scikit-learn library. K-means partitions data points into k clusters based on their distance to k randomly initialized centroids. 
It is widely used for customer segmentation, market basket analysis, and image compression.

* hierarchical clustering - it is available in Scipy library. Hierarchical clustering builds a dendrogram that represents the hierarchy of nested clusters 
by merging or splitting them based on the similarity or distance between them. It is a powerful technique that can handle data with complex structures,
such as time-series, graphs, and trees.

* DBSCAN - available in Scikit-learn library that can handle data with arbitrary shapes and sizes. It works by identifying dense regions of data points that are 
separated by sparse regions or noise. It is widely used for anomaly detection, image segmentation, and recommender systems.

## Advanced clustering techniques

* spectral clustering
* affinity propagation 
* mean shift

These are available in Scikit-learn and other Python libraries and  are more complex and computationally intensive than k-means and hierarchical clustering,
but they can provide better clustering results for data with complex structures or high-dimensional spaces.

Depending on the data structure, size, and complexity, one can choose the appropriate clustering algorithm to achieve the desired clustering results.

** Clustering in python - Code

The file data_clustering_code.ipynb has some clustering techniques. To run the code:
* Download  data_clustering_code.ipynb and clustering_sample_lending_data.xlsx and add to the same folder.
  *  If using other data with both categorical and numeric variables, be sure to change the column names accourdingly
* Open jupyter notebook and run



