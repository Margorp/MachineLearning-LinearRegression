# MachineLearning-LinearRegression

Linear Regression is a statistic method to solve the best fitting line from a set of given data.

Let's assume you have a set of data with two features, so it is a 2-dimensional data set that can be plotted on a graph.
Two set features are stored in X vector and y vector.
Parameters that we are going to solved are theta vector.

![](https://latex.codecogs.com/gif.latex?y=\theta_{0}+\sum\limits^{m}_{j=0}\theta_{1}X)

To make the calculation more convenient, we set X[1] to be X and X[0] be the vector with same size with values equal to 1.

![](https://latex.codecogs.com/gif.latex?y=\sum\limits^{1}_{i=0}\theta_{i}X_{i})

![](https://latex.codecogs.com/gif.latex?h(\theta;X)=\sum\limits^{n}_{i=0}\theta_{i}X_{i})

m is the total size of data.
