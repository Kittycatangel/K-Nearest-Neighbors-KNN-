# K-Nearest-Neighbors-KNN

# Introduction

There are two important parameters to the KNeighbors classifier: the number of neighbors and how you measure distance between data points.
In order to find the nearest neighbor of a given point, you need to calculate the Euclidean distance between two points.
Given two points, p p1 p2 , ,pn , and q q q , ,q1 2 n , the distance between p and q is given by the following formula:

                            ![image](https://user-images.githubusercontent.com/53411455/139564282-0739ff2d-4cf9-4fa0-b8fa-4478eb8d497b.png)


# Data

Iris data 

# Method

Implement KNN model

## KNN K=1
                        ![image](https://user-images.githubusercontent.com/53411455/139564303-22af5b6d-bca3-4fb9-ba0e-42175169f7d7.png)


## KNN K= 100

                          ![image](https://user-images.githubusercontent.com/53411455/139564318-346b7284-dc98-4a8a-8c7a-8c647be89331.png)


## Finding optimal K
To find the optimal k, you simply find the value of k that gives the highest accuracy. Or, in this case, you will want to find the lowest misclassification error (MSE). The following code snippet finds the MSE for each k, and then finds the k with the lowest MSE. It then plots a line chart of MSE against k.

                              ![image](https://user-images.githubusercontent.com/53411455/139564331-66cde75e-6815-4338-9c8f-e04db6580813.png)


# Conclusion

One of the strengths of k-NN is that the model is very easy to understand, and often gives reasonable performance without a lot of adjustments. Using this algorithm is a good baseline method to try before considering more advanced techniques. So, while the nearest k-neighbors algorithm is easy to understand, it is not often used in practice, due to prediction being slow and its inability to handle many features.
