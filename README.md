# CANCERAPI

This project aims to predict the presence of breast cancer based on a dataset of features extracted from breast mass images. The dataset contains various attributes related to the breast mass, such as radius, texture, perimeter, area, smoothness, and more.

We will be using a deep learning model created using TensorFlow and Keras to classify the breast cancer diagnosis into malignant (1) or benign (0).

## Dependencies

- pandas
- scikit-learn
- TensorFlow

## Dataset

The dataset used in this project is named `cancer.csv`. The dataset consists of several features related to the breast mass, along with the diagnosis (1=malignant, 0=benign).

## Model

The model is a simple feedforward neural network with the following architecture:

- Input layer with 256 units and a sigmoid activation function
- Hidden layer with 256 units and a sigmoid activation function
- Output layer with 1 unit and a sigmoid activation function

The model is trained using the Adam optimizer and binary crossentropy as the loss function.

## Usage

To run the project, simply execute the provided Python script. The script will load the dataset, preprocess it, split it into training and testing sets, create and compile the model, and finally train the model on the training data.

After the training is complete, you can evaluate the model on the test dataset to see its performance.
