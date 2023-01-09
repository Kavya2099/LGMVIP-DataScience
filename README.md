# LGMVIP-DataScience
This repository contains projects created for LGMVIP- DataScience virtual internship

IDE: **Google Colab**

# Task 1: Image to Pencil Sketch with Python


**OpenCV** (Open Source Computer Vision Library) is an open-source computer vision and machine learning software library.

## Steps to do the pencil sketch

* Read the image in RGB format
* Convert it to grayscale
* Convert the image to a negative image which is also known as Inverted grayscale to enhance the details
* Next blur the negative image and invert the blurred image
* Finally mixing up grayscale and inverted blurred image

# Task 2: Handwritten Digit Recognition using Neural Networks

A **neural network** is a series of algorithms that endeavors to recognize underlying relationships in a set of data through a process that mimics the way the human brain operates.

For our project here, we'll use **MNIST** dataset.

The MNIST dataset is an acronym that stands for the **Modified National Institute of Standards and Technology** dataset. It is a dataset of **60,000 small square 28×28 pixel grayscale images** of handwritten single digits between **0 and 9**.

## Steps

* Split up the dataset into training and testing set
* Normalizing the dataset
* Creating model
* Compiling the model
* Fitting the model
* Saving the model
* Making predictions
