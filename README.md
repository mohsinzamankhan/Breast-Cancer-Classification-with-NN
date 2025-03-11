# Breast Cancer Classification with Neural Networks

## Overview
This project implements a **Neural Network (NN)** for classifying breast cancer as **benign** or **malignant** using the **Breast Cancer Wisconsin dataset** from Scikit-learn. The goal is to develop a deep learning model that accurately distinguishes between the two types of tumors.

## Dataset
The dataset used in this project is the **Breast Cancer Wisconsin (Diagnostic) dataset** from Scikit-learn. It contains **30 numerical features** derived from digitized images of breast masses, along with labels indicating whether the cancer is benign (0) or malignant (1).

### Features:
- The dataset includes **30 features** related to the characteristics of cell nuclei, such as:
  - Radius
  - Texture
  - Perimeter
  - Area
  - Smoothness
  - Compactness
  - Concavity
  - Symmetry, etc.

### Target:
- **1**: Benign (non-cancerous)
- **0**: Malignant (cancerous)


## Implementation
The model follows these steps:
1. **Load the dataset** using Scikit-learn.
2. **Preprocess the data** (normalization and train-test split).
3. **Build a Neural Network** using TensorFlow/Keras.
4. **Train the model** with appropriate loss and optimizer.
5. **Evaluate performance** using accuracy and confusion matrix.
6. **Visualize results** through plots.

### Model Architecture
- Input Layer: 20 neurons (corresponding to dataset features)
- Hidden Layers: 1 dense layers with ReLU activation
- Output Layer: 2 neuron with sigmoid activation (binary classification)


## Results
- Expected accuracy: **95%**



