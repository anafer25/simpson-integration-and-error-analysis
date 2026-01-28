# simpson-integration-and-error-analysis

## overview
this program implements simpson's 1/3 rule to approximate the definite integral of a function. it also evaluates the accuracy of the method by computing the absolute error compared to the exact integral value. the error is plotted against the step size on a log-log scale to visualize the order of accuracy.

## objectives
* implement simpson’s integration routine in python
* approximate the integral of a given function over a specified interval
* compute the absolute error for different step sizes
* plot log(error) vs log(step size) to determine the convergence order graphically

## method
* define the function to integrate
* implement simpson’s 1/3 rule for a specified number of intervals
* calculate the integral for an initial number of intervals (4 intervals)
* double the number of intervals iteratively for a total of 10 evaluations
* compute the absolute error as the difference between the approximation and the exact value
* plot the logarithm of the error against the logarithm of the step size
