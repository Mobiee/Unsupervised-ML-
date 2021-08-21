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

<img src="https://raw.githubusercontent.com/Mobiee/Unsupervised-ML-/main/Graphs/chart1.png?token=APEXWSPEULA6LZGGCEVVOFDBEBHLQ" height="300" width="350" alt="Pie Chart">

Looking at the distribution of Gender in the mall Data, as shown in Figure there is more female
customer in the mall as compared to males. Female customers are about 56% while male customers
are about 44 % in the mall.

<img src="https://raw.githubusercontent.com/Mobiee/Unsupervised-ML-/main/Graphs/chart2.png?token=APEXWSPEULA6LZGGCEVVOFDBEBHLQ" height="300" width="350" alt="bar Chart Income">

As visualised above most customers have an annual income of 54k$ and 78k$, while some customers
have the lowest income of 15K$ to highest income of 137K$ which are less as compared to those who
have an income of 54k$ and 78k$.

<img src="https://raw.githubusercontent.com/Mobiee/Unsupervised-ML-/main/Graphs/chart3.png?token=APEXWSPEULA6LZGGCEVVOFDBEBHLQ" height="300" width="350" alt="Bar chart for Age">

The distribution plot of Age shows that most customers are in their 30’s followed by those who are 19
years and 40 years old. The customers who are 55, 56, 64 and 69 years old shop less in the mall as
compared to other age groups.

<img src="https://raw.githubusercontent.com/Mobiee/Unsupervised-ML-/main/Graphs/chart4.png?token=APEXWSPEULA6LZGGCEVVOFDBEBHLQ" height="300" width="350" alt="Bar chart for Age">

The above pair plot does not show that there is any significant difference between male and female
customers, which could be an indication that gender does not play a role in connection to consumer
segmentation/clustering.


### Applying KMeans Clustering Algorithms
In this section, KMeans Algorithm attempts to partition the dataset into K distinct non-overlapping
clusters, with each data point belonging to only one group or cluster. It attempts to keep intra-cluster
data points as close as possible while making clusters as separate (far) as possible. It assigns data points
to clusters based on the number of squared distances [1].

<img src="https://raw.githubusercontent.com/Mobiee/Unsupervised-ML-/main/Graphs/chart5.png?token=APEXWSPEULA6LZGGCEVVOFDBEBHLQ" height="300" width="350" alt="Elbow cahrt">

The below Figure shows the clustering plot of the data where the red points are cluster 0, green is
cluster 3, golden are cluster 2 and blue is cluster 1.

<img src="https://raw.githubusercontent.com/Mobiee/Unsupervised-ML-/main/Graphs/chart6.png?token=APEXWSPEULA6LZGGCEVVOFDBEBHLQ" height="300" width="350" alt="Elbow cahrt">


### In summary :
Cluster 0 belongs to low income who have a high spending score, where most people are people are
younger aged and the ratio of females is higher than that of males.
Cluster 1 belongs to high income and low spending score, where the average age is 47 and the ratio of
males are higher than that of females.
Cluster 2 belongs to average income and average spending score who are older people and the ratio of
females are higher than males.
Cluster 3 belong to people with high income and high spending scores who are in their 30s where the
ratio of males is higher than females.

<img src="https://raw.githubusercontent.com/Mobiee/Unsupervised-ML-/main/Graphs/chart7.png?token=APEXWSPEULA6LZGGCEVVOFDBEBHLQ" height="300" width="350" alt="Elbow cahrt">



