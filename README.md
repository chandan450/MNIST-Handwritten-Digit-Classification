# Handwritten Digit Recognition using Machine Learning and Deep Learning

## MNIST dataset:

MNIST is a collection of handwritten digits from 0-9. 
Image of size 28 X 28

# Requirements

* Python 3.5 +
* Scikit-Learn (latest version)
* Numpy (+ mkl for Windows)
* Matplotlib

# Introduction
MNIST contains 70,000 images of handwritten digits: 60,000 for training and 10,000 for testing. The images are grayscale, 28x28 pixels, and centered to reduce preprocessing and get started quicker. 

Keras is a high-level neural network API focused on user friendliness, fast prototyping, modularity and extensibility. It works with deep learning frameworks like Tensorflow, Theano and CNTK, so we can get right into building and training a neural network without a lot of fuss.

## Description
This is a 5 layers Sequential Convolutional Neural Network for digits recognition trained on MNIST dataset. I chose to build it with keras API (Tensorflow backend) which is very intuitive. 

## Accuracy
It achieved 99.51% of accuracy with this CNN trained on a GPU, which took me about a minute. If you dont have a GPU powered machine it might take a little longer, you can try reducing the epochs (steps) to reduce computation.

It achieved 98.15% of accuracy on test set of this CNN model trained on GPU.
