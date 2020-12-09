# Analyzing K-Means Clustering Algorithms with Multiple Centroid Initializations and Distance Measures using PySpark

This project was developed as part of my Master's Course Study in Algorithms and Methods of Big Data Analytics.

Authors: Prudhviraj Sheela, Aman Masipeddi

The main motive of this project is to understand the fine details of implementing clustering algorithms such as K-Means and K-Means++ using Spark and also it helps in understanding the impact of multiple cluster initialization and distance measures. The process flow includes 3 steps and they are:

a)Initializing K-Centroids for Spark using the data given in both K-Means and K-Means++ Algorithms.

b)Computing both the Eucledian and Manhattan Distances for the initial obtained k-centroids in both the algorithms.

c)Measuring the clustering algorithm performance using Cost functions for Eucledian and Manhattan Distances.

d)Comparing the performance of two algorithms and their cost functions by the line plots obtained between cost function and number of iterations.

IDE Used: Google Colab Notebook

Language Used: Python

Description about the files:

1)Project-3.pdf: This file contains the steps associated for developing the application and also the intermediate output formats for executing the program.

2)K-Means.py: PySpark K-Means clustering program developed with multiple centroid initializations and distance measures and its associated internal steps.

3)K-Means++.py: PySpark K-Means++ clustering program developed with multiple centroid initializations and distance measures and its associated internal steps.

4)data.txt: This file contains the associated input data to be processed for obtaining the centroids.

5)K-Centroids for (K-means++).txt: This data file contains the initial centroids obtained in K-Means++.py file.

6)K-Centroids for (K-Means).txt: This data file containd the initial centroids obtained in K-Means.py file.

Output Files: The explanation about the output generated is available in "K-Means.py" and "K-Means++.py" python file which explains clearly each step on how is the end result obtained. 










