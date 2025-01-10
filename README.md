
# Convolutional Neural Network (CNN) from Scratch

## Overview
This repository demonstrates the implementation of a **Convolutional Neural Network (CNN)** from scratch, including:
- Fundamental classes (`Value`, `Neuron`, `Layer`, `MLP`) to build neural networks.
- Custom implementation of 2D convolution (`Conv2D`) with stride, padding, and bias.
- Activation functions (`ReLU`, `Tanh`) and pooling operations (`MaxPooling`).
- Example input images and operations.

## Features
- **Custom Framework**:
  - Backpropagation and gradient computation using the `Value` class.
  - Flexible neural network construction using `Neuron`, `Layer`, and `MLP`.
- **Convolutional Operations**:
  - Sliding window convolution with configurable parameters.
  - Support for ReLU activation and max pooling.
- **Example Visualization**:
  - Visualizations of convolutional filters and output images.


## Requirements
- Python 3.x
- NumPy
- Matplotlib

## Example Input and Output
### Input Image
![Input Image](examples/input_image.jpeg)

### Convolution Output
![Convolution Output](examples/conv_output.png)

