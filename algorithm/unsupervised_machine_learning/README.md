# Unsupervised Learning

Unsupervised learning is a category of machine learning algorithms that operate on unlabeled data. These algorithms discover hidden patterns or intrinsic structures from the input data without the use of specific target outcomes or rewards. Unsupervised learning is often used for exploratory data analysis and it is an important step in preprocessing raw data for supervised learning. The main types of unsupervised learning include [clustering](#clustering),[anomaly detection](#anomaly-detection-and-novelty-detection), [visualization and dimensionality reduction](#visualization-and-dimensionality-reduction), and [association rule learning](#association-rule-learning). `Currently, this repository only contains [K-means](./Kmeans.ipynb) and [DBSCAN](./DBSCAN.ipynb) and [PCA](./PCA.ipynb). I will add more algorithms in the future.`

## Clustering

Clustering algorithms group data points into distinct clusters based on their similarity. The goal is to separate the data such that data points in the same cluster are as similar as possible, while data points in different clusters are as dissimilar as possible. Examples of clustering algorithms include:
- [**K-means**](./Kmeans.ipynb): A centroid-based algorithm that partitions data into K clusters, minimizing the sum of squared distances between data points and their respective cluster centroids.
- [**DBSCAN**](./DBSCN.ipynb): A density-based clustering algorithm that groups together data points that are closely packed together, marking low-density areas as noise.
- **Hierarchical Clustering Analysis (HCA)**: A family of algorithms that build nested clusters by merging or splitting groups of data points, forming a tree-like structure.
- **Mean Shift**: A non-parametric, density-based clustering algorithm that identifies clusters based on the mode (peak) of the underlying probability density function.
- **OPTICS**: A density-based clustering algorithm similar to DBSCAN, but with the ability to handle datasets with varying densities.

## Anomaly Detection and Novelty Detection
Anomaly detection is about identifying unusual data points in your dataset, which can be useful for fraud detection, fault detection, or removing outliers from data before applying other algorithms. Novelty detection, on the other hand, is about identifying new observations that are different from the training data. Both techniques are useful for ensuring the quality and integrity of data. Examples of anomaly and novelty detection algorithms include:
- **One-class SVM**: A modification of the Support Vector Machine algorithm for identifying data points that are significantly different from the majority of the data.
- **Isolation Forest**: An ensemble-based method that identifies anomalies by isolating observations in a random decision tree structure.
- **Local Outlier Factor (LOF)**: A density-based algorithm that measures the local deviation of a data point's density compared to its neighbors.
- **Elliptic Envelope**: A statistical method that fits an ellipse to the central data points, identifying outliers as those falling outside the ellipse.

## Visualization and Dimensionality Reduction
Visualization algorithms are unsupervised learning algorithms that help to represent high-dimensional data in a low-dimensional space, making it easier for humans to understand. Dimensionality reduction algorithms reduce the number of features in a dataset while preserving its structure or useful information. Examples include:
- [**Principal Component Analysis (PCA)**](./PCA.ipynb): A linear dimensionality reduction technique that transforms data to a new coordinate system, retaining the most significant variance while discarding the least significant variance.
- **Kernel PCA**: An extension of PCA that incorporates a kernel function to allow for non-linear dimensionality reduction. This is particularly useful when the underlying structure of the data is not linear.
- **t-SNE**: A non-linear dimensionality reduction technique that minimizes the divergence between two probability distributions over pairwise similarities of the data points in the high-dimensional and low-dimensional spaces.
- **UMAP (Uniform Manifold Approximation and Projection)**: A non-linear dimensionality reduction technique that assumes the data lies on a manifold and approximates this manifold using a graph-based representation.
- **Independent Component Analysis (ICA)**: A technique that separates a multivariate signal into additive, statistically independent subcomponents, often used for blind source separation.
- **Non-negative Matrix Factorization (NMF)**: A dimensionality reduction technique that decomposes a non-negative matrix into a product of two lower-rank non-negative matrices, often used for data with non-negative values such as image or text data.


## Association Rule Learning
Association rule learning is a machine learning method that is used to identify interesting relations or associations among a set of items. This technique is commonly used in market basket analysis, where the goal is to find associations between products that customers buy together. Examples include:
- **Apriori**: An algorithm for frequent item set mining and association rule learning over transactional databases. It proceeds by identifying the frequent individual items in the database and extending them to larger and larger item sets, as long as those item sets appear sufficiently often in the database.
- **FP-Growth**: An algorithm that exploits an (extended) prefix-tree (FP-tree) structure to store the database in a compressed form. FP-Growth uses this data structure to extract frequent itemsets without the need for candidate generation.
- **Eclat**: A depth-first search algorithm that uses set intersection to compute the support of a candidate itemset. It is particularly efficient for datasets with lots of items but relatively small transactions.
