# Hand-Written-Digit-Recognition
This project implements a handwritten digit recognition system using a Convolutional Neural Network (CNN), built with TensorFlow and Keras, to classify images from the MNIST dataset.

## Project Overview
The goal of this project is to accurately classify handwritten digits (0-9) from grayscale images. The MNIST dataset, which contains 70,000 images of handwritten digits, is used for training and evaluating the model. Each image is 28x28 pixels in grayscale.

## Features
**Data Preprocessing:** Normalizes the images for better model convergence.
**CNN Architecture:** Uses multiple convolutional layers, max pooling, and dense layers to classify digits.
**Model Training:** Trained over 5 epochs with accuracy and loss metrics.
**Prediction and Visualization:** Outputs predictions along with the actual digits for sample test images.

## Dataset
The MNIST dataset is loaded from TensorFlow's keras.datasets API.  
It contains:  
60,000 training images  
10,000 test images  
Each image represents a digit from 0 to 9 and is labeled with the corresponding digit.

## Model Architecture
The CNN model architecture includes:  
**Convolutional Layers:** Extracts features from images.  
**Max Pooling Layers:** Reduces the spatial dimensions, helping to generalize and prevent overfitting.  
**Flatten Layer:** Converts the 2D matrices to a 1D vector before passing to dense layers.  
**Dense Layers:** Fully connected layers for classification.  
**Output Layer:** 10 neurons with softmax activation to classify digits 0-9.  

