# Clustering through K-means
In this Notebook I made a script that clusters data collected from 149 respondents on their lifestyle, behaviours, willingness to pay, etc.
1. The script starts off with an example of differential privacy, this so you can report (aggregated) information while ensuring no privacy loss.
2. The notebook creates an elbow chart, as the K-means required a specified amount of clusters you can use this elbow chart to figure out the correct amount of clusters wherein heterogeneity is ensured between the groups while similarity is high within the groups
3. The notebook shows you a loose example of a Hit rate in which the implications of clustering on a variable is offset to a group that was not clustered.
4. As there are 41 different variables that you would like to chart it seems wise to reduce the amount of dimensions of the data by using their Principal Components, in this form the variance of the data is ensured in two different dimensions so a scatterplot can be made with the data points and centroids correctly represented in space.
