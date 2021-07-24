# Facial-Expressions
## Problem Statement
<b>CLASSIFY THE EXPRESSION OF FACE IN IMAGE OUT OF Eight BASIC HUMAN EXPRESSION</b>

## Description
In this project, we are predicting the facial expressions of the eight most basic human expressions: 'anger', 'surprise', 'disgust', 'fear','neutral','happiness','sadness','contempt'.

## Source Data
We have to downloaded data from https://github.com/muxspace/facial_expressions .<br>
Here images folder consists of all the images and in data, legend.csv consists of the images name and the expressions associated with the images.

## Code Information
We use the Keras model.fit_generator to train the model with categorical_crossentropy as the loss function and adam as the optimizer. ReLU is used as the activation function in the Conv2D, hidden layer, and Softmax in the output layer. Early Stopping is used to stop early when the val_accuracy is not increasing much. To convert images to an array and one hot encode label we have used ImageDataGenerator and made different directories for different emotions in training and testing.

## Prerequisites
You need to have installed the following software and libraries on your machine before running this project.
1. Python 3
2. Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy, PIL.
3. TensorFlow
4. Keras
## Installing
1. Python 3: https://www.python.org/downloads/
2. Anaconda: https://www.anaconda.com/download/
3. Tensorflow: pip install tensorflow
4. Keras: pip install keras