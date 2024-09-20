# Handwritten-Digits-Classification
This project demonstrates a simple implementation of handwritten digits classification using deep learning with the Keras library.

The goal of this project is to create a neural network that can take an image of a digit (28x28 pixels, flattened to a 1D array of 784 values) and classify it into one of 10 possible categories, corresponding to digits from 0 to 9.

DATASET - The MNIST dataset consists of grayscale images of handwritten digits. It is a widely used benchmark for image classification tasks. Each image is 28x28 pixels, and there are 60,000 training images and 10,000 test images.

MODEL ARCHITECTURE - A simple neural network is used with the following structure:

Input layer: 784 nodes (one for each pixel in the flattened 28x28 image).
Output layer: 10 nodes (corresponding to the digit classes 0-9).
Activation function: Sigmoid activation is used in the output layer to ensure that the output values are between 0 and 1.
Loss function: Sparse categorical cross-entropy, as the problem is a multi-class classification task with integer labels.
Optimizer: Adam optimizer is used to adjust the weights of the network based on the loss function.
