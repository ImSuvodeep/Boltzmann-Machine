Movie Recommendation System using AutoEncoders with RBM
Overview
This repository contains Python code for building a Movie Recommendation System based on AutoEncoders with Restricted Boltzmann Machines (RBM). The system is trained on the MovieLens 1M dataset and evaluates its performance on a separate test set.

Getting Started
Mount Google Drive: Open the code in a Google Colab notebook and mount your Google Drive to access the dataset.

Import Libraries: Import the necessary libraries.

Load Dataset: Load the MovieLens dataset.

Data Preparation
Prepare Sets: Prepare the training set and the test set.

Convert Data: Convert the data into arrays and get the number of users and movies.

Data Conversion Function: Define a function to convert the data into an array with users in lines and movies in columns.

Tensor Conversion: Convert the data into Torch tensors and ratings into binary ratings (1 for Liked, 0 for Not Liked).

Neural Network Architecture (RBM)
RBM Class: Create the architecture of the Neural Network (RBM).
Training
Training Process: Train the RBM on the training set, and monitor the loss for each epoch.
Testing
Testing Process: Test the trained RBM on the test set and calculate the test loss.
Results
The training process outputs the loss for each epoch, and the test loss is reported after evaluating the system on the test set.

Author
Suvodeep Chowdhury

Acknowledgments
This code is based on the MovieLens dataset and AutoEncoder with RBM concepts.
Special thanks to the creators of the MovieLens dataset.
License
This project is licensed under the MIT License.
