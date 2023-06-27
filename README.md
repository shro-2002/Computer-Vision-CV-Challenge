# Computer Vision Challenge - PyTorch

This repository contains the code for a computer vision challenge using PyTorch. The challenge involves training a ResNet50 pretrained model on the Oxford 102 Flowers dataset.

## Dataset
The dataset used for this challenge is the Oxford 102 Flowers dataset, which consists of 102 different categories of flowers. The dataset is divided into training, validation, and test sets. The dataset can be downloaded from [here](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/).

## Installation
To run the code, you need to install the required dependencies. You can install them using the following command:

```shell
!pip install ipywidgets

# Code Overview

The code in this repository provides an implementation of a computer vision challenge using PyTorch. The following is an overview of the code's functionality:

1. Importing the required libraries and checking for available GPUs.
2. Counting the number of images in the dataset directory.
3. Defining the dataset class for the Oxford 102 Flowers dataset.
4. Splitting the dataset into training, validation, and test sets using the provided data splits.
5. Visualizing the images in the training and validation sets.
6. Defining the data loaders for training, validation, and test sets.
7. Defining the model architecture by loading a pretrained ResNet50 model and modifying the last fully connected layer.
8. Freezing the layers of the pretrained model except for the classifier layer.
9. Defining the loss function, optimizer, and learning rate scheduler.
10. Moving the model to the available device (GPU or CPU).
11. Printing the model summary.
12. Training the model for a specified number of epochs and saving the best model.
13. Plotting the training and validation losses and accuracies.
14. Testing the trained model on the test set and calculating the accuracy.
15. Visualizing the images in the test set with their predicted labels.

## How to Use

To use this code for the computer vision challenge, follow these steps:

1. Install the required dependencies.
2. Download the Oxford 102 Flowers dataset and place it in the specified directory.
3. Run the provided code step by step, following the instructions and comments.
4. Adjust the hyperparameters and experiment with different settings to improve the model's performance.

Feel free to modify the code and adapt it to your specific needs. 
