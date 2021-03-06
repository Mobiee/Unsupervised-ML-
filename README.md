# Unsupervised-ML DBSCAN and KMEANS
Exploring Unsupervised-ML

## Introduction
This repository provides information regarding various steps taken to find and apply several suitable
clustering algorithms to conduct unsupervised learning on the data. K-means and DBSCAN are chosen
to perform, these algorithms are applied to the data separately and their performance is compared by
appropriate evaluation tools and recommends the algorithm with better performance for
Clustering of data.

## Data Exploratory analysis
In order to understand and examine the data and features of data, data exploratory analysis is
performed, to get an insight into the data and its relationship between the features.
Before performing EDA, the data is checked to see how the data provided looks like.

<img src="https://raw.githubusercontent.com/Mobiee/Unsupervised-ML-/main/Graphs/chart1.png?token=APEXWSLG6V5JGOZBXBNSEG3BEBIL2"  width="350" height="300" alt="Pie Chart">



Looking at the distribution of Gender in the mall Data, as shown in Figure there is more female
customer in the mall as compared to males. Female customers are about 56% while male customers
are about 44 % in the mall.

<img src="https://raw.githubusercontent.com/Mobiee/Unsupervised-ML-/main/Graphs/chart2.png?token=APEXWSK647O6M5CFH3BYJOTBEBIZY" height="300" width="350" alt="bar Chart Income">

As visualised above most customers have an annual income of 54k$ and 78k$, while some customers
have the lowest income of 15K$ to highest income of 137K$ which are less as compared to those who
have an income of 54k$ and 78k$.

<img src="https://github.com/Mobiee/Unsupervised-ML-/blob/main/Graphs/chart3.png?raw=true" height="300" width="350" alt="Bar chart for Age">

The distribution plot of Age shows that most customers are in their 30’s followed by those who are 19
years and 40 years old. The customers who are 55, 56, 64 and 69 years old shop less in the mall as
compared to other age groups.

<img src="https://github.com/Mobiee/Unsupervised-ML-/blob/main/Graphs/chart4.png?raw=true" height="300" width="350" alt="Bar chart for Age">

The above pair plot does not show that there is any significant difference between male and female
customers, which could be an indication that gender does not play a role in connection to consumer
segmentation/clustering.


### Applying KMeans Clustering Algorithms
In this section, KMeans Algorithm attempts to partition the dataset into K distinct non-overlapping
clusters, with each data point belonging to only one group or cluster. It attempts to keep intra-cluster
data points as close as possible while making clusters as separate (far) as possible. It assigns data points
to clusters based on the number of squared distances [1].

<img src="https://github.com/Mobiee/Unsupervised-ML-/blob/main/Graphs/chart5.png?raw=true" height="300" width="350" alt="Elbow cahrt">

The below Figure shows the clustering plot of the data where the red points are cluster 0, green is
cluster 3, golden are cluster 2 and blue is cluster 1.

<img src="https://github.com/Mobiee/Unsupervised-ML-/blob/main/Graphs/chart6.png?raw=true" height="300" width="350" alt="Elbow cahrt">


### In summary :
Cluster 0 belongs to low income who have a high spending score, where most people are people are
younger aged and the ratio of females is higher than that of males.
Cluster 1 belongs to high income and low spending score, where the average age is 47 and the ratio of
males are higher than that of females.
Cluster 2 belongs to average income and average spending score who are older people and the ratio of
females are higher than males.
Cluster 3 belong to people with high income and high spending scores who are in their 30s where the
ratio of males is higher than females.

<img src="https://github.com/Mobiee/Unsupervised-ML-/blob/main/Graphs/chart7.png?raw=true" height="300" width="350" alt="Summary Table">

### References:
* [1] Dabbura, I., 2018. K-means Clustering: Algorithm, Applications, Evaluation Methods, and Drawbacks.
[online] Medium. Available at: <https://towardsdatascience.com/k-means-clustering-algorithm-applicationsevaluation-
methods-and-drawbacks-aa03e644b48a>.
* [2] Scikit-yb.org. 2021. Elbow Method — Yellowbrick v1.3.post1 documentation. [online] Available at:
<https://www.scikityb.
org/en/latest/api/cluster/elbow.html#:~:text=K%2Dmeans%20is%20a%20simple,number%20(k)%20of%2
0clusters.&text=The%20elbow%20method%20runs%20k,average%20score%20for%20all%20clusters.>
.
* [3] dzone.com. n.d. KMeans Silhouette Score Explained With Python Example - DZone AI. [online] Available
at: <https://dzone.com/articles/kmeans-silhouette-score-explained-with-python-exam> .
* [4]Grootendorst, M., 2019. Cluster Analysis: Create, Visualize and Interpret Customer Segments. [online]
Medium. Available at: <https://towardsdatascience.com/cluster-analysis-create-visualize-and-interpretcustomer-
segments-474e55d00ebb> .
* [5]Maklin, C., 2019. DBSCAN Python Example: The Optimal Value For Epsilon (EPS). [online] Medium.
Available at: <https://towardsdatascience.com/machine-learning-clustering-dbscan-determine-the-optimalvalue-
for-epsilon-eps-python-example-3100091cfbc>.
* [6] Singh Chauhan, N., 2019. What is Hierarchical Clustering? - KDnuggets. [online] KDnuggets. Available at:
<https://www.kdnuggets.com/2019/09/hierarchical-clustering.html>.

