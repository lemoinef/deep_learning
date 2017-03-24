# Week 5 Of The Deep Learning Nanodegree

## Structure

This week, we had 1 lesson:

- Intro to Tensorflow

Most of deep learning useful application is about solving perception problems (computer vision, speech recognition). Most big tech companies are tackling deep learning problems.

Deep learning is a powerful set of tools. Now a lot of tools are used in all sorts of problems (vision, speech, etc.).

A lot of work about deep learning as been done in the 80's and 90's, but computing power was not enough. Today, fast GPUs help us.  

### Hello TensorFlow!
TensorFlow’s api is built around the idea of a computational graph, a way of visualizing a mathematical process which you learned about in the MiniFlow lesson. 

### TensorFlow Math
You can add with 
`x = tf.add(1, 6) # = 7`, subtract with `y = tf.subtract(10, 6)`, multiply with `z = tf.mutiply(2, 5)`

### TensorFlow Transition
We:
- Ran operations in tf.Session.
- Created a constant tensor with tf.constant().
- Used tf.placeholder() and feed_dict to get input.
- Applied the tf.add(), tf.subtract(), tf.multiply(), and tf.divide() functions using numeric data.
- Learned about casting between types with tf.cast()
