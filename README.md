# CIFAR-10 Image Classification with ResNet Model

![Demo of the project](demo.gif)

This project involves building a deep learning model based on the ResNet architecture to classify images from the CIFAR-10 dataset.

## Key Features

- **Model Development**: Designed and implemented a ResNet-based model for image classification.
- **Data Preprocessing**: 
  - Applied data augmentation techniques to enhance model generalization.
  - Performed normalization using NumPy.
  - Visualized images using Matplotlib.
- **Model Performance**: Achieved a classification accuracy of **92.4%** using standard ResNet blocks and full pre-activation bottleneck blocks with PyTorch.
- **GPU Acceleration**: Utilized GPU hardware (CUDA and MPS) to accelerate training, reducing training time by 70%.

## Tools and Libraries
- PyTorch
- NumPy
- Matplotlib
- CUDA / MPS for GPU acceleration

## Usage
To use this repository, clone it and install the necessary dependencies. Then, run the training script to train the model on the CIFAR-10 dataset.
