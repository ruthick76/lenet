# Handwritten Digit Recognition Using LeNet

## Overview
This project implements a Convolutional Neural Network (CNN) using the LeNet architecture to recognize handwritten digits (0-9) from the MNIST dataset. The model is trained to classify 28x28 grayscale images while addressing challenges such as variations in handwriting styles, distortions, and different orientations.

## Features
- Uses the MNIST dataset for handwritten digit recognition.
- Implements the classic LeNet-5 architecture.
- Achieves high accuracy on the test dataset.
- Supports visualization of predictions and model performance.
- Includes training and evaluation scripts.

## Dataset
- **Dataset**: MNIST (Modified National Institute of Standards and Technology)
- **Number of Classes**: 10 (Digits 0-9)
- **Image Size**: 28x28 pixels, grayscale
- **Training Samples**: 60,000
- **Testing Samples**: 10,000

## Model Architecture (LeNet-5)
LeNet-5 consists of:
1. **Input Layer**: 28x28 grayscale image
2. **Convolutional Layer 1**: 6 filters of size 5x5, followed by activation (ReLU)
3. **Pooling Layer 1**: Max pooling (2x2)
4. **Convolutional Layer 2**: 16 filters of size 5x5, followed by activation (ReLU)
5. **Pooling Layer 2**: Max pooling (2x2)
6. **Fully Connected Layer 1**: 120 neurons
7. **Fully Connected Layer 2**: 84 neurons
8. **Output Layer**: 10 neurons (Softmax for classification)

## Requirements
To run this project, install the following dependencies:
```bash
pip install tensorflow keras numpy matplotlib
```

 
## Results
- **Training Accuracy**: ~99%
- **Testing Accuracy**: ~98%
- **Loss Function**: Cross-Entropy Loss
- **Optimizer**: Adam/SGD

## Visualization
- Confusion matrix for analyzing misclassifications.
- Sample predictions with true labels.
- Accuracy and loss curves during training.

   
