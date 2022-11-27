# Binary Classification of 3D CT Scans using Convolutional Neural Network

## Overview

Classifications models are used to to classify between different classes based on the data provided. Classifications models are of two types, binary and multiple classes. Binary Classification is classifying predicting whether an input belongs to either of the two classes whereas the Multiple Classes model decides in which class the input belongs since there are multiple classes to choose from. Classification algorithms include K-Nearest Neighbor, Decision Trees, Random Forests, Support Vecotr Machines etc. all included in the Scikit-Learn module of Python. Here we will perform Binary Classification to predict whether the supplied 3D images have disease or not. We will use 3D Computed Tomography(CT) Scan images and Convolutional Neural Networks.

## Convolutional Neural Network

Used a five layer Convolutional Neural Network(CNN) each layer containing:
- Input layer
- The hidden layer consists of:
    * Conv3D with Activation function ReLu
    * MaxPool3D
    * BatchNormalization
- Output Layer containing the Sigmoid Activation function
Used the Adams Optimizer for optimization

## Training Data

<div>
  <img src="https://github.com/Soumadeep03/CTScan_Classifier/blob/main/Train_1.PNG" height="200" width="200"><img/>
  
