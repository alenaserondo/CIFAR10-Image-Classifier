# CIFAR10-Image-Classifier
A machine learning project using a Convolutional Neural Network (CNN) to classify images into 10 different categories using Python and PyTorch 

## Overview 
This project implements a CNN trained on the CIFAR-10 dataset. The aim is to teach a neural network to recognise and classify different objects in small colour images 

## Dataset 

The CIFAR-10 dataset contains 60,000 colour images divided into 10 classes : 
- Plane
- Car
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

The dataset consists of 50,000 training images and 10,000 testing images 

## Model Architecture 

The model uses a Convolutional Neural Network consisting of : 
- Two convolutional layers
- Max pooling layers
- ReLU activation functions
- Three fully connected layers

## Technologies Used 
- Python
- PyTorch
- Torchvision
- NumPy
- Jupyter Notebook
- VS Code

# How to Run 
1. Clone or download this repository
2. Install the required dependencies :
pip install -r requirements.txt 
3. Open cnn.ipynb in VS Code or Jupyter Notebook
4. Select your Python kernel
5. Run all cells

# Results 
- Achieved approximately 67.54% accuracy on the CIFAR-10 test dataset.
- Tested the trained model on additional external images.
- The model struggled to correctly classify many external images, often producing predictions with low confidence.
- This highlighted the challenges of generalisation when applying a model to images outside its original training dataset. 
