# MNIST Handwritten Digit Recognition using CNNs

## Overview

This project implements a Convolutional Neural Network (CNN) using Keras and TensorFlow to classify handwritten digits from the [MNIST dataset](http://yann.lecun.com/exdb/mnist/).  

## Training Details

- **Optimizer**: RMSprop
- **Loss Function**: Categorical Crossentropy
- **Batch Size**: 64
- **Epochs**: 5
- **Normalization**: Pixel values scaled to [0, 1]
- **Label Encoding**: One-hot encoding

## Results

| Metric           | Value      |
|------------------|------------|
| Test Accuracy    | ~99.32%    |

