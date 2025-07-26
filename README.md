# Convolutional Neural Network for Handwritten Digit Recognition

This project implements a Convolutional Neural Network (CNN) using Keras/TensorFlow to classify handwritten digits from the MNIST dataset. The model demonstrates deep learning concepts including data preprocessing, CNN architecture design, training, and evaluation.

## Features

- Data Preprocessing: Automatic normalization and reshaping of MNIST image data for optimal CNN input
- CNN Architecture: Multi-layer convolutional neural network with batch normalization and ReLU activation
- Training Pipeline: Complete model compilation, training, and evaluation workflow
- Visualization Tools: Built-in functions to visualize training data and model predictions
- Performance Metrics: Accuracy and loss tracking during training and testing
Prediction Analysis: Visual comparison of actual vs predicted digit classifications

## Requirements
- Python 3.7+
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Installation

1. Clone the repository:
`git clone https://github.com/yourusername/conv-neural-network.git`

2. Navigate to the project directory:
`cd conv-neural-network`

3. Create a virtual environment (recommended):
`python -m venv cnn_env`
`source cnn_env/bin/activate  # On Windows: cnn_env\Scripts\activate`

4. Install required dependencies:
`pip install tensorflow keras numpy matplotlib seaborn jupyter`

## How to Use

Option 1: Run the Jupyter Notebook
1. Start Jupyter Notebook:
`jupyter notebook`

2. Open the notebook:
- Navigate to `ImplementCNN.ipynb` in your browser
- Run all cells sequentially to see the complete workflow

Option 2: Run as Python Script
1. Convert notebook to Python script (if needed):
`jupyter nbconvert --to python ImplementCNN.ipynb`

2. Execute the script:
`python ImplementCNN.py`
