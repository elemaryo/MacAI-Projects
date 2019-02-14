# MacAI MNIST Challenge

Submission deadline: Thursday Feb 28th 2019

![alt text](https://raw.githubusercontent.com/Jzar/MacAI-MNIST-Challenge/master/MNIST.png)

*fig. 1* A sample of the MNIST dataset. 

## What is MNIST?

**MNIST** = (Modified National Institute of Standards and Technology database) 

MNIST is a dataset of hand-written digits, stored as a 28x28 pixel image, and labelled according to what number it is (0,1,2,..,9). 
These labels could each be said to be a class, and then all of the 9 shaped images are "classified" as 9s, the 0s are classified as 0, etc.
The problem of taking any non-known piece of data ( in this case, a hand written number), and assigning it to a class is called a classification
problem. Training a classifier on the MNIST dataset is often many people's *first* machine learning problem!

MNIST is often considered the "Hello World!" of AI.

Creating a ruleset for properly classifying  all possible handwritten digits is a very, very hard problem, if you were to do it manually.
Through the use of machine learning techniques, properly classifying the images can be accomplished with relative ease!

## Challenge Details

To support our beginning members, we are running an open competition to see who can produce the model that makes the least mistakes, i.e the most accurate.

Models may only be trained on the "training" split of the MNIST dataset, and will only be assessed on the "testing" split.

A mistake will be defined as the predicted label for a test value *not* matching the actual label.

You're encouraged to try out several different model types to see performs best!

## Help

Since MNIST classification is such a classic problem, there are no shortage of resources available online for creating a simple and short program. Feel free to use what you can find to help your understanding!

The purpose of this exercise to *not* to create a model from scratch, but to become comfortable in modifying hyperparameters of a model, and learning what impacts it may have.

A hyperparameter is some parameter of a model that must be set by the modeller. They have a great impact on how a model will behave, so they are worth experimenting with!

As well, I will be adding to a "Solutions" folder in this repository with different implementations using different types of models. Feel free to look at these, and use them to learn more!

### MacAI ML Tutorials

If you are not attending our machine learning tutorials, I'd highly recommend it. 

This content may be review for some members, but if you're starting from scratch check out the [the github](https://github.com/akiljames83/MacAI-2018). It would be invaluable while working on this project



## Dependencies

If you choose to reference my implementation(s) of an MNIST classifyier you would require Python3 and the following libraries, installable from PIP

- Python3

- Tensorflow

- Keras

- Scikit-Learn

It is recommended that you use Python3, and Keras if you are a beginner, because of their 
