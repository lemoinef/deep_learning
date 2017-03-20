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

### Preparing for Siraj's Lesson

### Siraj's Sentiment Analysis
