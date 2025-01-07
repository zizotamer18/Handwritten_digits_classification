# Handwritten_digits_classification

This project implements a **Feedforward Neural Network (FNN)** to classify handwritten digits from the **MNIST dataset** using TensorFlow/Keras. The MNIST dataset is a collection of grayscale images of digits (0–9) commonly used for training and testing image processing systems.

## Features
- Preprocesses data by normalizing pixel values and flattening images.
- Defines and trains a simple neural network with one hidden layer.
- Evaluates performance using accuracy and a confusion matrix.
- Visualizes input samples and results.

## Dataset
The MNIST dataset contains:
- **60,000 training images**
- **10,000 test images**
Each image is 28x28 pixels in grayscale.

## Model Architecture
- **Input Layer**: Flatten layer to convert 28x28 images into 1D vectors (784 values).
- **Hidden Layer**: Fully connected layer with 12 neurons and ReLU activation.
- **Output Layer**: Fully connected layer with 10 neurons (one per digit) and sigmoid activation.

## Requirements
- Python 3.13.0
- TensorFlow
- NumPy
- Matplotlib
- Seaborn

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/handwritten-digit-recognition.git
   cd handwritten-digit-recognition

2. Install dependencies:
   ```bash
   Copy code
   pip install tensorflow matplotlib numpy seaborn

3. Run the script:
   ```bash
   python mnist_digit_recognition.py

## Output
-Training accuracy and loss.
-Predicted labels for test images.
-Confusion matrix heatmap for model evaluation.
-Example Visualizations
-Sample images with their labels.
-Confusion matrix showing predicted vs actual labels.

## License
This project is licensed under the MIT License. Feel free to use and modify it as needed.