# Deep Learning Image Classification - Fashion MNIST

## Objective
Build a deep learning model using TensorFlow/Keras to classify Fashion MNIST clothing images.

## Dataset
Fashion MNIST Dataset

- 60,000 training images
- 10,000 testing images
- Image size: 28×28 grayscale
- 10 clothing categories

## Preprocessing
- Normalized pixel values
- Split into training and testing datasets

## Deep Learning Model
Sequential Neural Network consisting of:

- Flatten Layer
- Dense (128 neurons, ReLU)
- Dropout (0.2)
- Dense (64 neurons, ReLU)
- Dense (10 neurons, Softmax)

Optimizer:
- Adam

Loss Function:
- Sparse Categorical Crossentropy

## Results

Test Accuracy:
87.75%

## Training Graphs

- Training vs Validation Accuracy
- Training vs Validation Loss

## Saved Model

fashion_mnist_model.keras

## Author

VishalSuresh1309
