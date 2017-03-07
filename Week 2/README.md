# Week 2 Of The Deep Learning Nanodegree

## Structure

This week, we had 2 lessons and 1 project:

- Siraj's Neural Network
- Intro to Neural Networks
- Project 1


### Siraj's Neural Network
This consisted of a video where we coded a neural network in python.

### Intro to Neural Networks
We went through logistic regression, gradient descent, neural networks, perceptron, ect.

#### Logistic Regression
We use the log loss function to minimize the error function and we use gradient descent to reduce the number of errors.

#### Neural Networks
Some times, multiple lines can be used (in a 2d context) to adequately reduce the error in classification. A simple neural network can be used to return the answer depending on the condition that we program (e.i. is it in this or that space: yes or no?) We can then "stack" multiple questions together (it is similar to a decision tree, but we add an operator).

#### Perceptron
"Data, like test scores and grades, is fed into a network of interconnected nodes. These individual nodes are called perceptrons or neurons, and they are the basic unit of a neural network. Each one looks at input data and decides how to categorize that data. In the example above, the input either passes a threshold for grades and test scores or doesn't, and so the two categories are: yes (passed the threshold) and no (didn't pass the threshold). These categories then combine to form a decision -- for example, if both nodes produce a "yes" output, then this student gains admission into the university."

The perceptron is trained with weights (starting with a random value) that are updated as the neural net is trained. A higher weight value means the input value is more important to the final output.

After training the neural net, the final result of the perceptron's summation is turned into an output signal. This is done by feeding the linear combination into an activation function. One simple activation function is the Heaviside step function which returns 1 if x is greater than 0 or 0 if x is smaller/equal to 0.



### Project 1
The first project consisted of building a neural net to predict bike rentals.
