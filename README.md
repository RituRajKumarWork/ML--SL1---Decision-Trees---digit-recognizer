# CIFAR-10 Image Classification using Decision Trees

## Project Overview

This project implements a Decision Tree classifier to classify images from the CIFAR-10 dataset, which consists of 60,000 32x32 color images in 10 classes. The model is trained to identify objects based on features extracted from these images.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Evaluation](#evaluation)
- [Image Classification](#image-classification)
- [Image Comparison](#image-comparison)
- [Conclusion](#conclusion)

## Technologies Used

- Python
- TensorFlow/Keras
- scikit-learn
- Matplotlib
- Google Colab (for easy access to GPU and data handling)

## Dataset

The project uses the **CIFAR-10 dataset**, which is a widely used benchmark in the machine learning community for image classification tasks. The dataset includes 10 different classes:

1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

### Downloading the Dataset

The CIFAR-10 dataset is automatically downloaded using the Keras library in the provided code, so no manual download is required.

## Installation

You can run this project directly in Google Colab. 

You may need to install the required libraries if they are not already available:

```bash
!pip install -q scikit-learn matplotlib
