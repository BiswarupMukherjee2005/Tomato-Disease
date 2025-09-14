# Tomato Disease Classification

This repository contains a machine learning model for classifying tomato leaf images into different disease and pest categories using TensorFlow and Keras. The model is trained on the PlantVillage dataset from Kaggle, focusing on identifying tomato health conditions based on image data.

## Overview

The project implements a custom Convolutional Neural Network (CNN) to classify tomato leaf images into multiple classes, including diseases, pests, and healthy conditions. The model dynamically adapts to the number of classes detected in the dataset and includes data augmentation for improved performance.

- **Dataset**: PlantVillage Tomato Diseases and Pests Dataset (available on Kaggle).
- **Framework**: TensorFlow/Keras.
- **Classes**: Dynamically detected (e.g., 10 or 15 classes based on dataset structure).
- **Features**: Training, validation, accuracy/F1 score evaluation, and prediction on new images.

## Requirements

To run this project, install the required Python libraries listed in `requirements.txt`. Use the following command:

```bash
pip install -r requirements.txt
