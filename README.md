# Handwritten-Digits-Classification
This project demonstrates a simple implementation of handwritten digits classification using deep learning with the Keras library.

The goal of this project is to create a neural network that can take an image of a digit (28x28 pixels, flattened to a 1D array of 784 values) and classify it into one of 10 possible categories, corresponding to digits from 0 to 9.

DATASET - The dataset used in this project is the MNIST (Modified National Institute of Standards and Technology) dataset, which is one of the most widely recognized datasets for image classification tasks. 

Total Samples: 70,000 images
Training Set: 60,000 images
Test Set: 10,000 images
Image Size: 28 x 28 pixels (grayscale images)
Number of Classes: 10 (representing the digits 0 to 9)
Pixel Range : 0-255

![image](https://github.com/user-attachments/assets/a9eeec60-4aa8-44e8-962d-d90775cb1eed)



MODEL ARCHITECTURE - A simple neural network is used with the following structure:

Input layer:   784 nodes (one for each pixel in the flattened 28x28 image).

Hidden Layer: The hidden layer consists of 100 neurons with ReLU activation, which allows the model to learn more complex patterns in the data.

Output layer:   10 nodes (corresponding to the digit classes 0-9).

Activation function:   
ReLU (Rectified Linear Unit) is used in the hidden layer to introduce non-linearity and help the network learn complex patterns.
Sigmoid activation is used in the output layer to ensure that the output values are between 0 and 1.

Loss function:   Sparse categorical cross-entropy, as the problem is a multi-class classification task with integer labels.

Optimizer:   Adam optimizer is used to adjust the weights of the network based on the loss function.

Metrics: The model is evaluated based on accuracy

ACCURACY : 97%

GUI

The GUI is built using Tkinter library, allowing users to to draw digits on a canvas and predict the corresponding digit using the trained neural network model.


![image](https://github.com/user-attachments/assets/1557a288-ff01-4c11-b622-1e07ab80a6f2)
