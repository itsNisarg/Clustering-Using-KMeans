# Clustering-Using-KMeans
Learnt Clustering using KMeans on the iris dataset as part of my internship @ The Sparks Foundation

It makes use of the KMeans module of the Scikit Learn library.
It identifies the 3 flower species of the iris genus : Iris setosa, Iris virginica and Iris versicolor

The KMeans algorithm works by choosing random points as centroids and assigning the data points to the nearest centroid.
Then it optimises on the distance between the nearest datapoints and the centroid and shifts the centroid such that the distance is minimised.
Finally we get the clusters from the data.

NOTE : The algorithm itself does not know how many clusters are there in the data. We need to specify it beforehand as a model parameter.
