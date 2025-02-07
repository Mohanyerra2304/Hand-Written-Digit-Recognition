# Hand-Written-Digit-Recognition


## Project Overview
The goal of this project is to accurately classify handwritten digits (0-9) from grayscale images. The MNIST dataset, which contains 70,000 images of handwritten digits, is used for training and evaluating the model. Each image is 28x28 pixels in grayscale.

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

