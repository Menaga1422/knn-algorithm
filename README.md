# knn-algorithm
#ml

	• KNN is a algorithm that classifies data points based on the points that are most similar to it.
	• Algorithm that stores all available cases and classifies new cases based on similarity measure (distance functions)

The KNN Algorithm
1.Load the data
2.Initialize K to your chosen number of neighbors
3. For each example in the data
3.1 Calculate the distance between the query example and the current example from the data.
3.2 Add the distance and the index of the example to an ordered collection
4. Sort the ordered collection of distances and indices from smallest to largest (in ascending order) by the distances
5. Pick the first K entries from the sorted collection
6. Get the labels of the selected K entries
7. If regression, return the mean of the K labels
8. If classification, return the mode of the K labels

Pros :
	1. Easy to use
	2. Quick calculate time
	
Cons:
	1. Not applicable for large data
	2. Poor at classifying data points in a boundary where they can be classified one way or the other.

Refer the pynotebook for implementation of KNN using python 
