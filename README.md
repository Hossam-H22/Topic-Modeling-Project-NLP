# Topic-Modeling-Project-NLP

Topic modeling is a part of NLP that is used to determine the topic title for each similar group of documents based on the content. To achieve this in our project we used Clustering and Topic Modeling algorithms. Five algorithms have been used which are LDA, K-means, Mini-batch K-means, NMF, and LSA. In the following sections, we will clarify each one of them in detail.

<br>

### Preprocessing

- Data reading and cleaning
  > Here we aimed to handle minor issues in the database including reformatting the data and removing the nulls.
- Feature extraction
  > Feature Extraction Makes Machine Learning More Efficient. It cuts through the noise, removing redundant and unnecessary data. This frees machine learning programs to focus on the most relevant data.


<br>

### Clustering and Topic Modeling algorithms
- Mini-batch K-means
  > The Mini Batch K-means algorithm is a variation of the traditional K-means algorithm that uses smaller random subsets or batches of data points to update cluster centers at each iteration. This approach makes the algorithm computationally efficient, particularly for large datasets. The Mini Batch K-means algorithm approximates the results of K-means while reducing the time and memory requirements, making it suitable for real-time and online clustering tasks.

- LSA Model
  > LSA (Latent Semantic Analysis) is a technique used for analyzing relationships between documents and terms within a large corpus. It represents documents and terms as vectors in a high-dimensional space and reduces the dimensionality to capture latent semantic meaning. LSA algorithm identifies patterns of word co-occurrence and similarity to uncover underlying semantic relationships in textual data.

- NMF Model
  > NMF (Non-Negative Matrix Factorization) is a matrix factorization technique used for dimensionality reduction and feature extraction. It assumes that the input matrix consists of non-negative values and decomposes it into two non-negative matrices representing a low-rank approximation of the original data. NMF algorithm extracts interpretable features by enforcing non-negativity constraints, making it useful for tasks such as text mining and image processing.

- LDA Model
  > LDA (Latent Dirichlet Allocation) is a probabilistic generative model used for topic modeling. It assumes that documents are composed of multiple topics, and each word in a document is generated from one of these topics. LDA algorithm infers the latent topic structure in each set of documents and assigns the most probable topics to each word.

- K-means Model
  > The K-means algorithm is an iterative clustering algorithm used to partition a dataset into k distinct clusters. It assigns each data point to the cluster with the nearest mean, iteratively updating the cluster centers until convergence. The algorithm aims to minimize the within-cluster sum of squared distances, resulting in compact and well-separated clusters.


<br><br>

### Conclusion
We started this project to determine the title for each cluster of articles and then assign the article used as test data in its suitable cluster. As we managed to implement the requirements successfully, we now can say that we proved that the Topic modeling algorithms, the LSA, LDA, and NMF, have approximately similar accuracy, which is higher than the general clustering algorithms accuracy, K-means, Mini-batch K-means.






<br><br>


![Project GUI](https://github.com/Dragon-H22/Topic-Modeling-Project-NLP/assets/88390970/62ce0618-afd9-4776-b49b-990bdae0e2e1)
