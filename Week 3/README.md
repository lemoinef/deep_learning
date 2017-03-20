# Week 3 Of The Deep Learning Nanodegree

## Structure

This week, we had 5 lessons:

- Model Evaluation and Validation
- Sentiment Analysis with Andrew Trask
- Intro to TFLearn
- Preparing for Siraj's Lesson
- Siraj's Sentiment Analysis

### Model Evaluation and Validation
- Testing: we must never use the testing dataset for training.

- Confusion matrix: After developping a model, we want to know how good is our model. We use true positive, true negative, false positive, false negative to assess the performance of the model.

- Accuracy: ratio between the correct classified points and total points.

- Regression Metrics:
  - mean absolute error (easy to calculate in sklearn)

  - mean squared error

  - r2 score (comparing the results with the simplest possible model (often a line)) If R2 is close to 1, this is a good model, else it's bad.  

- Types of Errors:
  - underfitting (high bias, oversimplify the problem, bad on training and testing set)
  - overfitting (high variance, overcomplicate the problem, great on training and bad on testing set)
  - good model (good on training and testing set)

- Model Complexity Graph
  - linear model
  - quadratic model
  - polynomial model

- K-Fold Cross-Validation
 we have k fold sets and we find the mean of all the test/train sets results after training our model.

### Sentiment Analysis with Andrew Trask

### Intro to TFLearn
We will learn about
- Activation functions: rectified linear units (ReLUs) and Softmax
- Classification cost function: Categorical Cross Entropy
- Sentiment Analysis with TFLearn
- Handwritten digit recognition with TFLearn

#### Activation functions
We used the sigmoid function as the activation function earlier on our hidden units. But this is not the only activation function you can use and actually has some drawbacks. The derivative of the sigmoid function maxes out at 0.25, which mean the error is shrunk by at least 75%, which mean the weight updates will be tiny. Sigmoids - because of that- have fallen out of favor.

Instead of sigmoids, most recent deep learning networks use rectified linear units (ReLUs) for the hidden layers. ReLU activations are the simplest non-linear activation function we can use. When the input is positive, the derivative is 1, so there isn't the vanishing effect we see with sigmoids. Frameworks like TensorFlow and TFLearn make it simple it use ReLU on hidden layers.

Sometimes, ReLUs can 'die' in training, the weight could be set in such as way that it never fires again. To prevent this, we must set an appropriate learning rate that is not too high.

In the case of the Softmax, it 'squashes' the outputs in order to have units in between 0 and 1. The output created by the softmax function is equivalent to a categorical probability distribution. The only difference between the sigmoid and the softmax is the 'squashed' effect on the output (equalling to 1)

#### Categorical Cross-Entropy
"we've been using the sum of squared errors as the cost function in our networks, but in those cases we only have singular (scalar) output values.

When you're using softmax, however, your output is a vector. One vector is the probability values from the output units. You can also express your data labels as a vector using what's called one-hot encoding.

This just means that you have a vector the length of the number of classes, and the label element is marked with a 1 while the other labels are set to 0."

### Preparing for Siraj's Lesson

### Siraj's Sentiment Analysis
