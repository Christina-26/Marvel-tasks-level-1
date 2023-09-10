**Curve fitting**
Curve fitting is a type of optimization that finds an optimal set of parameters for a defined function that best fits a given set of observations.
Unlike supervised learning, curve fitting requires that you define the function that maps examples of inputs to outputs.
The key to curve fitting is the form of the mapping function.

A straight line between inputs and outputs can be defined as follows:

y = a * x + b

Where y is the calculated output, x is the input, and a and b are parameters of the mapping function found using an optimization algorithm.


![curve fitting graph](https://github.com/Christina-26/Marvel-tasks-level-2/blob/main/curve%20fitting%20graph.png?raw=true)
![table curve fitting](https://github.com/Christina-26/Marvel-tasks-level-2/blob/main/table%20curve%20fitting.png?raw=true)

**Underfitting and overfitting**

First, curve fitting is an optimization problem. Each time the goal is to find a curve that properly matches the data set. There are two ways of improperly doing it — underfitting and overfitting.
Underfitting happens whenever the function barely captures the complexity of the distribution of data. A model with such a curve will make erroneous predictions because it attempts to simplify everything to a significant degree. It might, for example, capture just a few data points out of dozens.

Overfitting maximizes the accuracy of a model by fitting the curve perfectly.There are many potential ways to understand why overfitting is an issue. One is to think of any dataset as incomplete. An overfitted model would have learned the patterns so well that it would expect them to be identical in the future.

![overfitting-and-underfitting](https://github.com/Christina-26/Marvel-tasks-level-2/blob/main/overfitting-and-underfitting.png?raw=true)
