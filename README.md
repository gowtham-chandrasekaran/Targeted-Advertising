# Targeted-Advertising
Target advertisements to specific users based on their interests

# Data Source

https://www.cs.cmu.edu/~enron/

# Explanation
1.	Mahout is a powerful tool for machine learning purposes that was can use with Hadoop. I can use the K Means Clustering that is provided with the
Mahout to perform clustering of similar interest users.
2.	The K Means Clustering of Mahout will also provide us with the most frequent terms from the document in each cluster.
3.	As we are collecting the email dataset, Mahout can recognize different clusters and shows us the top features in each of the cluster. If we can cluster users based on what they talk on emails, we can know the most frequent words that they have used. So after clustering, all users will be clustered together with similar interests based on what they talk. Once this is done, we can advertise the same products to the users belonging to one cluster.
4.	As Mahout can take multiple input files for clustering, we can create separate txt files for each user.
5.	Each txt file will have the cleaned data that was mentioned in the previous answer such as stop words removal, special characters and numbers removal and so on.
6.	If we are working with words, there will be several features generated. This will increase the dimensionality of the dataset. We can use Principle
Component Analysis to reduce the dimensionality.
7.	The mahout commands have several parameters that can be used. I will experiment with them to find out what each does and use it for my analysis.
8.	The K Means Clustering of Mahout generated different vector files. To understand about where each user belongs, i.e, to which cluster they belong, we can use sequence dumper to dump the part-m-0000 file.
9.	The cluster dump command of Mahout will be used to dump a result file to see what were the frequent words that were used in each cluster.
10.	Most of the data preparation and preprocessing that were mentioned earlier will be done in the python code.
11.Finally the clusters can be plotted on a scatter plot for visualization and analysis.
