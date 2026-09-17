# Lab 3: CNN Architecture - The Four Building Blocks

## Overview
In this lab, I explored Convolutional Neural Networks (CNNs) and implemented their core components from scratch. The main goal was to understand how CNNs process images and how they achieve translation invariance compared to standard dense networks.

## What I Built
I implemented the four building blocks of a CNN architecture:
1. **Filtering (Convolution):** Implemented `convolve2d` and `conv_layer` to extract features using shared filters (e.g., Sobel edge detectors).
2. **Max Pooling:** Implemented `max_pool2d` and `maxpool_layer` to downsample feature maps, reducing parameters and building tolerance to small shifts.
3. **Flatten:** Implemented `flatten_layer` to convert 3D feature maps into a 1D vector.
4. **Fully Connected:** Used `Layer_Dense` (from Lab 2) to classify the features and output final probabilities.
