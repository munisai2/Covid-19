# Image Classification for COVID-19 Detection

## Overview
This project aims to classify medical images into three classes: normal, pneumonia, and COVID-19 using advanced deep learning architectures. The implemented models include VGG16, ResNet, and Inception v3.

## Model Architectures and Performance

### VGG16
- Architecture: 16 layers with 3x3 convolutional filters and max-pooling layers.
- Accuracy: 96.97%

### ResNet
- Architecture: Utilizes residual learning with hundreds of layers.
- Accuracy: 81.82%

### Inception v3
- Architecture: Incorporates multiple convolutional filters in parallel for efficient feature capture.
- Accuracy: 87.88%

## Comparative Analysis
- Metrics Evaluated: Accuracy, precision, recall, F1 score, confusion matrix, AUROC.
- Results: VGG16 outperformed with superior performance across all metrics.

## Project Structure

### Data Preparation
- Data set: https://www.kaggle.com/datasets/pranavraikokte/covid19-image-dataset
- The dataset is very small. So it should be easy for you to run this on your systems or Google Colab.
- The dataset consists of images from 3 classes – normal, pneumonia and COVID.

### Methodology
- Build an image classification model that can classify the images into the 3 classes
- Build a two layer image classification model: 
- First classify into normal and abnormal
- Classify abnormal images into COVID and pneumonia



