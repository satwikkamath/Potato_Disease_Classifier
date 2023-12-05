# Potato Disease Classifier

This repository implements a Convolutional Neural Network (CNN) using TensorFlow to classify potato diseases. The model distinguishes between early blight, late blight, and healthy potatoes based on the PlantVillage dataset.

## Overview

- **Dataset:** The "PlantVillage" dataset is utilized for training and testing the model.
- **Model Architecture:** The CNN model is designed to categorize potato images into early blight, late blight, and healthy classes.
- **Data Preprocessing:** Training, validation, and test datasets undergo caching, shuffling, and prefetching for performance optimization.
- **Training:** The model is trained using the Adam optimizer and sparse categorical cross-entropy loss.
- **Prediction:** The repository includes a prediction function for making predictions on new images.
- **Visualization:** Sample predictions are visualized using `matplotlib` in the `make_predictions.py` script.


