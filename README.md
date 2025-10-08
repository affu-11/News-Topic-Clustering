# News-Topic-Clustering

**Project Title**

News Topic Clustering using Unsupervised Machine Learning

**Domain**

Natural Language Processing (NLP), Media & Journalism

1. The project belongs to the text mining & NLP domain, where the main goal is to extract hidden structures or groupings from large amounts of unlabelled news data.

2. This helps news agencies, content platforms, and aggregators to organize articles automatically into categories such as politics, sports, entertainment, business, and technology.

**Data Type**

Unstructured Text Data

Dataset contains news headlines or full articles.

Example format:

id	      headline

1    	"Government announces new policy for rural development"

2   	"Champions League final ends with dramatic penalty shootout"

3	    "Tech giants release AI-powered personal assistants"

**ML Techniques**

Text Preprocessing → Cleaning and normalizing text data.

Feature Extraction → Converting text into numerical representation using TF-IDF Vectorization.

Dimensionality Reduction → Using PCA (Principal Component Analysis) or t-SNE for visualization.

Clustering Algorithms → Primarily K-Means, optionally Hierarchical Clustering.

Evaluation → Using Silhouette Score & Davies-Bouldin Index to check cluster quality.

**Preprocessing Required**

Lowercasing (convert text to lowercase).

Remove punctuation, numbers & special characters.

Tokenization (split text into words).

Stopword Removal (remove common words like the, is, and).

Lemmatization (reduce words to root form → running → run).

TF-IDF Vectorization to represent text in numerical form.

**Dimensionality Reduction**

PCA (Principal Component Analysis): Reduce high-dimensional TF-IDF vectors into a smaller number of features while retaining most of the variance.

t-SNE (t-distributed Stochastic Neighbor Embedding): For better visualization in 2D/3D, especially to show distinct clusters of topics.

**Clustering Method**

K-Means Clustering (main approach)

Groups news headlines into k clusters.

Number of clusters (k) chosen using Elbow Method or Silhouette Score.

Hierarchical Clustering (optional)

Useful for creating a tree/dendrogram of topics.

**Evaluation Metrics**

Silhouette Score → Measures how well samples are clustered.

Davies–Bouldin Index (DBI) → Lower values indicate better clusters.

Visual Validation → Scatterplots of clusters in 2D/3D.

**Final Output**

Clustered Groups of News Articles

Example:

Cluster 0 → Politics/Government news

Cluster 1 → Sports news

Cluster 2 → Technology news

Cluster 3 → Entertainment/Movies

Cluster 4 → Business/Finance

Interactive 2D/3D visualization of clusters using Plotly.

Representative headlines per cluster to show interpretability.

**Tools & Libraries**

**Programming Language:** Python

**Data Handling:** pandas, numpy

**Text Preprocessing:** nltk, spacy, re

**Feature Extraction:** scikit-learn (TfidfVectorizer)

**Dimensionality Reduction:** scikit-learn (PCA), sklearn.manifold (t-SNE)

**Clustering:** scikit-learn (KMeans, AgglomerativeClustering)

**Visualization:** matplotlib, seaborn, plotly



**Business Applications**

Automatic categorization of online news articles.

Personalized news feeds for users.

Content-based recommendation systems.

Detecting trending topics in media.
