# MNIST Handwritten Digit Classification using Artificial Neural Network (ANN)

## Project Overview
This project implements an Artificial Neural Network (ANN) to classify handwritten digits from the MNIST dataset. The model is trained to recognize digits (0-9) with a high accuracy of approximately 97% on the test set.

## Dataset
The MNIST dataset contains 70,000 grayscale images of handwritten digits:
- 60,000 images for training
- 10,000 images for testing  
Each image is 28x28 pixels in size.

## Model Summary
- Input layer: 784 neurons (flattened 28x28 pixels)
- Hidden layers: Defined in the notebook (refer to MNIST.ipynb for details)
- Output layer: 10 neurons (digits 0-9)
- Activation functions: ReLU in hidden layers, Softmax in output layer

## Performance
- Achieved ~97% accuracy on the test set.
- Small overfitting observed with a 1-3% gap between training and validation accuracy, which is acceptable for this model and dataset.

## Overfitting Notes
The slight overfitting can be improved by:
- Adding dropout layers
- Early stopping
- Regularization (e.g., L2)

## File Structure
- `MNIST.ipynb` : Jupyter notebook containing the full implementation, training, and evaluation of the ANN model.

## Requirements
- Python 3.x
- TensorFlow / Keras (or PyTorch, depending on the notebook)
- NumPy
- Matplotlib (optional for visualizations)

## How to Run
1. Open `MNIST.ipynb` in Jupyter Notebook or JupyterLab.
2. Run all cells to train and evaluate the ANN model on the MNIST dataset.

## Conclusion
This notebook demonstrates a simple yet effective ANN for handwritten digit classification with strong performance. It can serve as a foundation for more advanced image recognition tasks.

---

*Created by Nayan*

