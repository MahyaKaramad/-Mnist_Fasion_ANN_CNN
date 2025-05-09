# Comparison of CNN and ANN using MNIST Fashion Dataset

## Overview
This project explores the performance of two neural network architectures, CNN and ANN, on the MNIST Fashion dataset. The goal is to identify which model achieves higher accuracy in classifying images of fashion items.

## Dataset
The MNIST Fashion dataset, a substitute for the original MNIST handwritten digits dataset, consists of 70,000 grayscale images across 10 fashion categories.

## Models
### Artificial Neural Network (ANN)
- **Architecture**: Consists of dense layers with activation functions.
- **Layers**: Input layer, hidden layers with ReLU activation, and an output layer with softmax activation.
- **Optimization**: Uses Adam optimizer.

### Convolutional Neural Network (CNN)
- **Architecture**: Includes convolutional layers, pooling layers, and dense layers.
- **Layers**: Conv2D layers with ReLU activation, MaxPooling layers, and a softmax output layer.
- **Optimization**: Employs Adam optimizer for training.

## Training
- **Epochs**: Models are trained for a set number of epochs with batch size specified.
- **Validation**: Split dataset into training and validation sets to monitor performance and avoid overfitting.

## Results
Detailed comparison of accuracy and loss metrics for both models over the training epochs. Visualizations include plots for accuracy and loss over epochs to illustrate model performance dynamics.

## Code Structure
- **Data Preprocessing**: Loading and normalizing the dataset.
- **Model Building**: Separate sections for constructing the ANN and CNN models.
- **Training**: Code to train models using Keras with TensorFlow backend.
- **Evaluation**: Accuracy assessment on the test dataset.
- **Visualization**: Plots of training/validation loss and accuracy.

## Environment
- **Python version**: Specified (e.g., Python 3.7)
- **Libraries**: TensorFlow, Keras, NumPy, Matplotlib

## How to Run
1. Ensure all dependencies are installed using `pip install -r requirements.txt` (ensure you have this file setup).
2. Run the notebook cells sequentially to preprocess data, build models, train, and evaluate.

## Conclusions
The report concludes with insights on model performance, highlighting which model (CNN or ANN) performs better on the fashion classification task and discussing potential reasons for observed performance disparities.

## Future Work
Suggestions for future work include experimenting with different model architectures, tuning hyperparameters, and applying data augmentation to improve model robustness.
