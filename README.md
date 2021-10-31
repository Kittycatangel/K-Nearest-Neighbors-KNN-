# K-Nearest-Neighbors-KNN

# Introduction

There are two important parameters to the KNeighbors classifier: the number of neighbors and how you measure distance between data points.
In order to find the nearest neighbor of a given point, you need to calculate the Euclidean distance between two points.
Given two points, p p1 p2 , ,pn , and q q q , ,q1 2 n , the distance between p and q is given by the following formula:
![image](https://user-images.githubusercontent.com/53411455/139564362-af415e72-1176-4faa-910d-575e5fc619ba.png)




# Data

Iris data 

# Method

Implement KNN model

## KNN K=1
![image](https://user-images.githubusercontent.com/53411455/139564377-d5e5396a-9426-4eea-be89-ec6bba20a59b.png)


                  


## KNN K= 100
                  ![image](https://user-images.githubusercontent.com/53411455/139564380-649946f0-4be4-49f4-9bce-15b7033f54c5.png)


                   


## Finding optimal K
To find the optimal k, you simply find the value of k that gives the highest accuracy. Or, in this case, you will want to find the lowest misclassification error (MSE). The following code snippet finds the MSE for each k, and then finds the k with the lowest MSE. It then plots a line chart of MSE against k.

![image](https://user-images.githubusercontent.com/53411455/139564385-ae4699ee-53cc-4024-9d61-76a35fe44f28.png)

                         

# Conclusion

One of the strengths of k-NN is that the model is very easy to understand, and often gives reasonable performance without a lot of adjustments. Using this algorithm is a good baseline method to try before considering more advanced techniques. So, while the nearest k-neighbors algorithm is easy to understand, it is not often used in practice, due to prediction being slow and its inability to handle many features.
