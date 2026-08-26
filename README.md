AI Image Classifier Using CNN

Project Overview

This project is an AI image classifier built using Python and TensorFlow.

The model uses a Convolutional Neural Network (CNN) to classify images into 10 different categories from the CIFAR-10 dataset.

Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Gradio
* Google Colab

Dataset

The project uses the CIFAR-10 dataset, which contains:

* 50,000 training images
* 10,000 test images
* 10 image categories

The categories are:

Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, and Truck.

Model

The classifier uses a Convolutional Neural Network with:

* Convolutional layers
* Max Pooling layers
* Flatten layer
* Dense layers
* Softmax output layer

Training and Results

The model was trained using the CIFAR-10 training dataset.

The model achieved a test accuracy of 67.31%.

The model was also tested with an uploaded image. For one automobile image, the model predicted Automobile with a confidence of 68%.

Interactive Interface

A Gradio interface was created to allow users to upload an image.

The interface displays the model’s top three predictions and their confidence scores.

What I Learned

Through this project, I learned how to:

* Load and prepare an image dataset
* Normalize image data
* Build a CNN using TensorFlow and Keras
* Train an image classification model
* Evaluate model performance
* Interpret accuracy and confidence scores
* Create an interactive AI interface using Gradio

Future Improvements

Possible improvements include:

* Increasing the model’s accuracy
* Training for more epochs
* Using data augmentation
* Experimenting with different CNN architectures
* Testing the model with more images

Project Goal

The goal of this project was to gain practical experience in artificial intelligence, computer vision, and machine learning by building an image classification system from the ground up.
