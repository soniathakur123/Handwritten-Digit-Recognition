# Handwritten-Digit-Recognition using Deep Learning (MNIST)
##Project Overview

This project demonstrates Handwritten Digit Recognition using Deep Learning with the MNIST dataset.
A Neural Network model is built using TensorFlow & Keras to classify handwritten digits (0–9).

The model learns patterns from images and predicts which digit is written in an image.

## What is Deep Learning?

Deep Learning is a subfield of Machine Learning that uses Artificial Neural Networks with multiple layers to learn patterns automatically from data.

Unlike traditional programming, deep learning models learn directly from examples such as images, text, or audio without manually defining rules.

## Definition:

Deep Learning is a technique that enables computers to learn complex patterns from large amounts of data using multi-layer neural networks.

##Purpose of the Project

The main objectives of this project are:
Understand basic Deep Learning workflow
Build a Neural Network model
Train a model on image data
Predict handwritten digits automatically
Learn image classification concepts

## Dataset Used
MNIST Dataset
The MNIST dataset is a standard dataset for beginners in Deep Learning.

It contains:
60,000 training images
10,000 testing images
Images of handwritten digits (0–9)
Image size: 28 × 28 pixels (grayscale)
Each image represents one digit.

## Technologies & Libraries Used

Python
TensorFlow
Keras
NumPy
Matplotlib

## Model Architecture

The Neural Network used in this project consists of:
Input Layer – Accepts 28×28 pixel images
Flatten Layer – Converts 2D image into 1D vector
Dense Hidden Layer – 128 neurons, ReLU activation
Output Layer – 10 neurons (digits 0–9), Softmax activation

# Project Workflow (Step-by-Step)
Step 1: Import Libraries
Required libraries such as TensorFlow, NumPy, and Matplotlib are imported.
Step 2: Load Dataset
MNIST dataset is loaded using TensorFlow’s built-in dataset loader.
Step 3: Data Normalization
Pixel values are scaled from 0–255 to 0–1 to improve training performance.
Step 4: Build Neural Network
A Sequential Deep Learning model is created.
Step 5: Compile Model
Model configuration includes:
Optimizer: Adam
Loss Function: Sparse Categorical Crossentropy
Metric: Accuracy
Step 6: Train Model
The model learns patterns from training images over multiple epochs.
Step 7: Evaluate Model
Model accuracy is tested using unseen test data.
Step 8: Prediction
The trained model predicts digits from test images.
Step 9: Visualization
Sample digit image is displayed using Matplotlib.

## Model Performance

The model achieves high accuracy on handwritten digit classification after training.

## Output:

Predicted Digit: 7
Actual Digit: 7


## How to Run the Project

Install required libraries:
pip install tensorflow numpy matplotlib

Run the Python file:
python digit_recognition.py

##Learning Outcome

Through this project, you will learn:
Basics of Deep Learning
Neural Network architecture
Image classification
Model training & evaluation
Prediction using trained models

👩‍💻 Author
Sonia Thakur
Email:soniathakur7298@gmail.com
