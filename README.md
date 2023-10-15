# Fashion MNIST AI 

## Description

This project aims to classify images from the Fashion MNIST dataset, which comprises grayscale images of 10 different clothing items. Each image is 28x28 pixels in size. The task involves building a machine learning model that can accurately predict the category of a given clothing image.

## Task

The primary challenge was to:

- Preprocess the Fashion MNIST dataset for model consumption.
- Construct and train machine learning models for image classification, and evaluate their performance.

## Solution

### Data Exploration & Preprocessing:

- **Dataset Overview**: Leveraged the Fashion MNIST dataset containing grayscale images of 10 clothing categories.
- **Reshaping**: Images were reshaped from flat arrays to 2D matrices suitable for model input.
- **Normalization**: Pixel values, originally between 0 and 255, were scaled to lie between 0 and 1.
- **One-hot Encoding**: Transformed integer labels into one-hot vectors.
- **Data Splitting**: Segregated the dataset into training and validation subsets.

### Modeling:

- **Deep Neural Network (DNN)**: Initial experiments involved a DNN model for classification.
- **Convolutional Neural Network (CNN)**: Explored CNNs to assess their performance against traditional DNNs.
- **Model Enhancements**: Introduced dropout, batch normalization, and weight regularization to combat overfitting and improve model accuracy. Additionally, fine-tuned the learning rate for better convergence.

### Evaluation:

- **Overfitting Detection**: Noticed overfitting trends post the third epoch, where training loss decreased but validation loss surged.
- **Mitigation Techniques**: Considered dropout, early stopping, regularization, and data augmentation to counteract overfitting.

## Tech Stack & Libraries Used

- **Programming Language**: Python
- **Deep Learning Library**: Keras
- **Data Manipulation**: NumPy
- **Visualization**: Matplotlib
