# Adaptive Weight Optimization Algorithm (AWOA) Implementation

This repository demonstrates the implementation of the Adaptive Weight Optimization Algorithm (AWOA) for addressing class imbalance in machine learning tasks. AWOA dynamically adjusts class weights during training based on model bias, providing robust performance even with heavily imbalanced datasets.

## Overview

The AWOA algorithm leverages a novel bias computation method and optimizes weight adjustments using an adaptive approach. It integrates seamlessly with deep learning models and is designed to handle real-world scenarios where data imbalance is prevalent. This implementation uses a Convolutional Neural Network (CNN) on the CIFAR-10 dataset for binary classification between two classes, with one class significantly downsampled to create an imbalanced dataset.

## Features

- **Dynamic Weight Adjustment**: AWOA dynamically updates class weights during training, using a bias calculation method to minimize class imbalance effects.
- **Integrated with Deep Learning Models**: Easily integrates into TensorFlow/Keras pipelines for practical applications.
- **Early Stopping and Model Checkpointing**: Incorporates early stopping and best model saving for efficient training.

## File Structure

- `awoa.py`: Contains the implementation of the AWOA class.
- `data_loader.py`: Handles CIFAR-10 dataset loading, filtering, and preprocessing for binary classification.
- `main.py`: Trains the CNN model using AWOA for dynamic weight updates and evaluates its performance.
- `README.md`: Provides an overview of the project and usage instructions.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/awoa-implementation.git
   cd awoa-implementation
