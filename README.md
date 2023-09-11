**Title**:
MNIST Classifier with Data Augmentation using TensorFlow


**README**:

# MNIST Classifier with Data Augmentation

This repository contains a TensorFlow-based implementation of a classifier for the MNIST dataset. The unique aspect of this project is the use of data augmentation techniques to artificially increase the size of the training set and improve model generalization.

## Features:
1. **Data Augmentation**: The model employs data augmentation strategies such as random rotations, width and height shifts, and horizontal flips to generate varied versions of the original MNIST images. This aids in enhancing the robustness of the classifier.
  
2. **Simple Neural Network**: Utilizes a simple feed-forward neural network with a hidden dense layer to perform classification.
  
3. **Performance Metrics**: Apart from accuracy, a confusion matrix is also generated to understand the classifier's performance in more detail.
  
4. **Training and Validation Plots**: Post training, accuracy and loss plots are provided for both training and validation datasets to visualize the model's performance over epochs.

## Implementation Details:
- The dataset used is the MNIST dataset, a collection of handwritten digits.
- Data augmentation is carried out using TensorFlow's `ImageDataGenerator` class.
- The neural network comprises a flattening layer, a dense layer with `relu` activation, a dropout layer, and an output dense layer with `softmax` activation.
- Model performance is assessed using accuracy as the metric, and cross-entropy as the loss function.
- The training process is visualized using accuracy and loss plots for both training and validation sets.

## How to Run:
To run the code, ensure you have `tensorflow` and its required dependencies installed. Execute the provided script, and you should see the training process followed by the evaluation metrics and plots.

