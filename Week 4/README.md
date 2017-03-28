# Week 4 Of The Deep Learning Nanodegree

## Structure

This week, we had 2 lessons:
- Siraj's Math Notation
- Miniflow

### Siraj's Math Notation
  - calculus
  - linear algebra
  - statistics

Siraj discusses how to prepare data for deep learning algorithms. Nothing new, mostly going over familiar processes in data science and machine learning. The first chapters of Python Machine Learning by Raschka can serve as the basis for this kind of work.

### Miniflow
 We will learn about differentiable graphs and backpropagation.

#### What is a Neural Network?
A neural network is a graph of mathematical functions such as linear combinations and activation functions. It consists of nodes and edges. layers between output and input layers are called hidden layers.

#### Forward Propagation
"By propagating values from the first layer (the input layer) through all the mathematical functions represented by each node, the network outputs a value. This process is called a forward pass."

#### Learning And Loss
Neural Networks can improve the accuracy of their outputs over time.A simple artificial neuron depends on three components:
- inputs
- weights
- bias
By varying the weights, we can vary the amount of influence any given input has on the output.The learning process of neural net happens with backpropagation: the network modifies the weights to improve the network's output accuracy.

#### Linear Transform

#### Sigmoid Function
The sigmoid function replaces the stepfunction with an elegant S-shaped curve. The sigmoid function makes decisions, with the given weighted features from some data, it indicates whether or not the features contribute to a classification. The process of learning is done through backpropagation and gradient descent ans updates the weigths and bias.  

#### Cost
Different names exist for the accuracy measurements of networks. It can be called loss or cost. To calculate the cost in this lab we will use the mean squared error.

"The cost, C, depends on the difference between the correct output, y(x), and the network's output, a. It's easy to see that no difference between y(x) and a (for all values of x) leads to a cost of 0.

This is the ideal situation, and in fact the learning process revolves around minimizing the cost as much as possible."

#### Gradient Descent or Journey to the Bottom of the Valley
"You can envision the cost as a hill or mountain and we want to get to the bottom.

Imagine your model parameters are represented by a ball sitting on a hill. Intuitively, we want to push the ball downhill. And that makes sense, but when we're talking about our cost function, how do we know which way is downhill?

Luckily, the gradient provides this exact information.

Technically, the gradient actually points uphill, in the direction of steepest ascent. But if we put a - sign in front of this value, we get the direction of steepest descent, which is what we want."
