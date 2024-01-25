
# Food Recognition System

## Overview

This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras for the purpose of image classification. The model is designed to recognize and classify different types of food, particularly fruits, based on input images.

## Project Structure

- **Model Definition:**
  - A Sequential model is used to create a linear stack of layers.
  - Convolutional and pooling layers for feature extraction.
  - Dropout and Flatten layers for regularization and data reshaping.
  - Dense layers for fully connected neural networks.
  - Compilation with RMSprop optimizer and categorical crossentropy loss.

- **Training:**
  - The model is trained on a dataset using the `fit` function with specified epochs.
  - Training history is saved to a JSON file for analysis.

- **Evaluation:**
  - The trained model is loaded for making predictions on new images.
  - Image preprocessing involves loading, resizing, and converting to NumPy arrays.
  - Predictions are printed, displaying the predicted probabilities.

- **Visualization:**
  - Training accuracy is plotted over epochs using Matplotlib.

## Usage

1. **Model Training:**
   - Use the provided training dataset and execute the training script.
   - Adjust hyperparameters as needed.

2. **Prediction:**
   - Load the trained model for predicting food items in new images.
   - Modify the input path and parameters accordingly.

3. **Visualization:**
   - Analyze training accuracy over epochs using the generated plot.

## Dependencies

- TensorFlow
- Keras
- Matplotlib
- NumPy
- JSON

## Files

- `model_training_script.py`: Script for training the CNN model.
- `prediction_script.py`: Script for making predictions on new images.
- `training_hist.json`: JSON file containing training history.
- `trained_model.h5`: Pre-trained model file.


---

Feel free to adjust and expand the sections based on your project's specific details. This template provides a comprehensive yet concise overview for readers to understand your food recognition system.
