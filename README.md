# MachineLearning-LinearRegression

Linear Regression is a statistic method to solve the best fitting line from a set of given data.

Let's assume you have a set of data with two features, so it is a 2-dimensional data set that can be plotted on a graph.
Two set features are stored in X vector and y vector.

Parameters that we are going to solved is a theta vector, m is the total size of data.

![](https://latex.codecogs.com/gif.latex?y=\sum\limits^{m}_{j=1}\theta_{0}+\theta_{1}X^{(j)})

To make the calculation more convenient, we set X[1] to be X and X[0] be the vector with same size with values equal to 1.

![](https://latex.codecogs.com/gif.latex?y=\sum\limits^{m}_{j=0}\sum\limits^{n}_{i=0}\theta_{i}X_{i}^{(j)})

To solve the parameters theta, we use squared errors to measure the cost of the function, which is denoted as J.

![](https://latex.codecogs.com/gif.latex?J(\theta)=\frac{1}{2}\sum\limits^{m}_{j}(\sum\limits^{n}_{i=0}\theta_{i}X_{i}^{(j)}-y^{(j)})^{2})

To minimize the cost, we take differentiation of cost function to find the gradient at the theta point.

![](https://latex.codecogs.com/gif.latex?\delta{J(\theta)}=\sum\limits^{m}_{j}(\sum\limits^{n}_{i=0}\theta_{i}X_{i}^{(j)}-y^{(j)})X^{(j)})

To update the theta, we take a step more close to the optimum point in every iteration, by a method called gradient descent. Alpha is the learning rate controlling the speed of convergence.

![](https://latex.codecogs.com/gif.latex?\theta_{i}:=\theta_{i}-\alpha\delta{J()})
