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
