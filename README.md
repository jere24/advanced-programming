# Group Project for the class "Programming with Advanced Computer Languages"
_**Johannes Cordier and Jeremia Stalder**_

Our goal for this group project was twofold: First, we wanted to get to know Python and how to use it for a real world project. Second, we wanted to learn new machine learning techniques and directly apply them.

TODO quick description of what we did in our project

## Data
> All data handling can be found in the file [data.ipynb](https://github.com/jere24/advanced-programming/blob/master/data_cleaning.ipynb)


## Random forest
> Everything related to the random forest can be found in the file [RandomForest function.ipynb](https://github.com/jere24/advanced-programming/blob/master/RandomForest%20function.ipynb)

A random forest is a procedure that consists of several uncorrelated trees on different subsets of the data and of different covariates. 
All trees have grown under a certain type of randomization during the learning process. 
The trees partition the sample in mutually exlusive groups with a top-down, greedy algorithm. 
To get the random forest prediction the one needs to compute the average prediciton over the several trees. 

Having trees with a lot of splits usually leads to overfitting and therefore to a high out-of-sample variance. 
To tackle this issue there a multiple hyperparameters that can be optimzied in-sample.

In our case we try to predict the quality of red and white wine by chemical characteristics of the respective wines. 
In the training sample we optimze the forest size, covariate selection, maximum depth of the tree, minimum sample size in a split, minimum sample size in a terminal leaf.
We tune these parameters by trying several grids of possible modelspecifications in the sample and keep the specification to predict the out-sample wine quality. 
After comparing the estimated predicitons with the actual wine quality. We estimate the mean squared error, accuracy and R-squared for the red and white wine speratly. 

The results are the following:



## Neural network
> Everything related to the random forest can be found in the file [NeuralNet.ipynb]()

## Comparison
> Everything related to the random forest can be found in the file [comparison.ipynb]()
TODO How do the two methods compare? Which one is better? 
