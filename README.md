# mnist_ffnn_classifier
## Overview
This project demonstrates how to build a simple feedforward neural network using **TensorFlow** and **Keras**. The model is trained to classify handwritten digits from the MNIST dataset.

## Model Architecture
- **Input Layer:** 784 features (28x28 pixel images, flattened)  
- **Hidden Layer:** 512 neurons, ReLU activation  
- **Output Layer:** 10 neurons (digits 0–9), softmax activation  

## Training Details
- **Optimizer:** Adam  
- **Loss Function:** Categorical Cross-Entropy  
- **Epochs:** 5  
- **Batch Size:** 128 (default)  
- **Dataset Preprocessing:** Pixel values normalized to [0, 1]  

## Results
- **Test Loss:** 0.0723  
- **Test Accuracy:** 97.9%  

## Files
- `mnist_ffnn_classifier.ipynb` – Google Colab notebook containing the implementation.  
