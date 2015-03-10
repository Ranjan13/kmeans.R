# kmeans.R


This is the implementation of kmeans algorithm in R-language. This is the part of my assignment. I didnot use any inbuilt packages given in the R. 
The program for K-means is implemented in R
R should be installed in the system.


Download :: http://cran.r-project.org/
HOW TO RUN:
-----------
>Rscript kmeans.R letter-recognition.dat
https://archive.ics.uci.edu/ml/machine-learning-databases/letter-recognition/letter-recognition.data

OUT PUT:
--------

*	The 20% of input data is used as test data and 80% is used as training data
	The out put will be in the form of 2 Matrices.
		1) Centroid Matrix
		2) Classified Matrix
	In Centroid Matrix each row represents the centroids
	In Classified Matrix (with dimension cluster number x test data) 
		classified matrix[i,j] = 1 => data point "j" is in cluster "i"
		else 0.
This code has been run on letter-recognition data with 26 clusters. It was run for multiple time and gave an error within the range [75%-79%].
