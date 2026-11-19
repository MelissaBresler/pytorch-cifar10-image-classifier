
# CIFAR-10 Image Classification with PyTorch

## Project Overview
This project implements a Convolutional Neural Network (CNN) using PyTorch to classify images from the CIFAR-10 dataset into 10 categories.

The model was trained and evaluated using Google Colab.

## Dataset
- 50,000 training images
- 10,000 testing images
- 10 image categories
- Image size: 32 × 32 pixels

## Technologies
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Pandas
- Scikit-learn
- Google Colab

## Model Architecture
- 2 Convolutional Layers
- ReLU Activation
- Max Pooling
- 2 Fully Connected Layers
- Adam Optimizer
- Cross-Entropy Loss

## Results
- Initial Test Accuracy: 67.46%
- Final Test Accuracy: 69.95%
- Training Epochs: 8

## Evaluation
The model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Key Findings
- Best recognized category: Ship (87.70%)
- Lowest accuracy category: Frog (54.70%)
- The model achieved improved accuracy after additional training.

## Future Improvements
- Experiment with data augmentation.
- Train using a GPU.
- Explore deeper CNN architectures.
- Improve classification accuracy.
