# Netflix-Movies-And-Tv-Shows-Clustering

In 2018, they released an interesting report which shows that the number of TV shows
on Netflix has nearly tripled since 2010. The streaming service’s number of movies has
decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly
tripled. It will be interesting to explore what all other insights can be obtained from the
same dataset.

Where we need to do Exploratory Data Analysis, Understanding what type of content
is available in different countries, Is Netflix has increasingly focusing on TV rather than
movies in recent years. (Find out), Clustering similar content by matching text-based
features.

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset
is collected from Flixable which is a third-party Netflix search engine.
In the first step, as for importing the raw data, the “NETFLIX MOVIES AND TV SHOWS
CLUSTERING .csv” dataset has been loaded and created a data frame out of it. And then
check over the statistical properties, know the shape and size of the dataset and
perform data cleaning over It which includes treating duplicate values, renaming the
rating feature into actual meanings, and handling NaN/ Null/ Missing Values of the
data with visualization of the missing values as a matrix plot.

In the second step, performed the exploratory data analysis and data visualization,
where different plot graphs have been used for the univariate and bivariate analysis to
make some inferences from the data. A hypothesis has been formed which came up
being partially rejected.

In the third step, the Feature Engineering where encoding (Label Encoder) the
categorical features, extracting best features, TF-IDF Vectorization, PCA to handle
dimensionality, Standard Scaler to balance data distribution, and Removing
Punctuation and Stopwords, are performed before modeling.

And at the last, two types of topic modeling and three types of data clustering
algorithms are being used to fit the data, wherein Affinity Propagation, Agglomerative
Clustering, and K-Means Clustering are for clustering, after which the Unsupervised ML
Clustering project concluded by revealing that the optimal number of clusters was
found to be 2 in K-Means Clustering with a silhouette coefficient value of 0.705 through
which we can say that the clusters are well apart from each other as the silhouette
score is closer to 1.
