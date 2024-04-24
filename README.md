# Using Transfer Learning in Image Classification Task

This repository contains a deep learning project aimed at classifying images of dogs and cats. 
The project demonstrates the application of transfer learning both online and offline to enhance the accuracy of classification tasks with limited computational resources.

## Project Description

This project leverages a pre-trained VGG16 model from the torchvision library as a base for feature extraction, followed by a custom classifier to differentiate between dog and cat images. The project is structured into two main notebooks:
- `Online_Transfer_Learning.ipynb`: Demonstrates online transfer learning where the feature extraction and classification steps are performed simultaneously during model training.
- `Offline_Transfer_Learning.ipynb`: Illustrates offline transfer learning, where features are first extracted and stored, and then used to train a separate classifier.

## Dataset

The dataset used for training and validation consists of images of dogs and cats, structured into separate training and validation directories. Each category (dogs and cats) is represented in a subfolder within these directories.

## Features

- **Transfer Learning**: Utilization of the VGG16 model for robust feature extraction.
- **Data Loading**: Custom data loaders for handling image datasets.
- **Image Preprocessing**: Transformations applied to the images for normalization and augmentation.
- **Model Training**: Details on the training process, including loss calculation and backpropagation.
- **Accuracy and Loss Tracking**: Metrics for monitoring training and validation performance over epochs.
- **Visualization**: Functions to display images and their labels from batches.

## Installation

To run this project, you will need to install Python and the following Python libraries:
- PyTorch
- torchvision
- NumPy
- matplotlib

You can install them using pip:
```bash
pip install torch torchvision numpy matplotlib
