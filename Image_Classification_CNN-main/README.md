# Image_Classification_CNN

# Fashion MNIST Classification using CNN

This project is a Convolutional Neural Network (CNN) implementation to classify images from the **Fashion MNIST** dataset. The dataset consists of 70,000 grayscale images of 10 different categories of clothing items.

## Project Overview

The goal of this project is to build a CNN model that can accurately classify the clothing items in the images into one of the following categories:

1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

## Features

- **Image Classification**: Uses CNN to classify images from the Fashion MNIST dataset.
- **Deep Learning Model**: Leverages multiple convolutional layers with max pooling, followed by fully connected layers.
- **Training & Validation**: Tracks accuracy and loss on both training and validation data.

## Dataset

- **Fashion MNIST**: A dataset of 28x28 grayscale images representing different clothing items, with 10 classes.
- **Size**: 60,000 training images and 10,000 test images.
  
Download the dataset from [Kaggle](https://www.kaggle.com/datasets/zalando-research/fashionmnist).

## Model Architecture

1. **Convolutional Layers**: Extract features from input images.
2. **Max Pooling**: Reduces spatial dimensions and computation.
3. **Flattening**: Converts 2D feature maps into a 1D vector.
4. **Dense (Fully Connected) Layers**: Perform classification based on extracted features.
5. **Softmax Output**: Provides a probability distribution over the 10 clothing categories.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/fashion-mnist-cnn.git
   cd fashion-mnist-cnn
