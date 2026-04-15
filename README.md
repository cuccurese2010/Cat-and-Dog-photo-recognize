Project Overview: Cat vs. Dog Image Classification
This project implements a Deep Learning model designed to distinguish between images of cats and dogs using a Convolutional Neural Network (CNN).

1. The Dataset
The project utilizes a comprehensive training archive containing 25,000 labeled images (12,500 cats and 12,500 dogs).
Goal: Train the algorithm to analyze visual patterns and predict the correct label for new images.
Labels: The model uses a binary classification system where 1 represents a Dog and 0 represents a Cat.

2. Pre-trained Model (.h5 file)
To save time and computational resources, the project includes a pre-trained model file named Cat_vs_dogs_classification.h5.
Compression: Due to its size, this file is compressed into a 4-part 7z archive (Cat_vs_dogs_classification.7z).
Setup: You must extract these files and place the resulting .h5 file into the root directory (main folder) of your Google Drive.
Function: This file contains the weights and architecture from previous training sessions, allowing the AI to recognize photos immediately without starting from scratch.

Convolutional neural network recognizes the image - scheme of work 
3. Training History & Visualization
The project also includes a history file.
Purpose: This file stores the logs (accuracy and loss metrics) from the training process.
Usage: It is specifically used by the Colab notebook (Cat_and_Dog_Trained.ipynb) to generate visual graphs. These graphs help you evaluate how well the model learned over time.
Location: Like the model file, this should be placed in the root directory of your Google Drive.

Quick Setup Instructions
Download the dataset and the 4-part compressed archive.
Extract the Cat_vs_dogs_classification.h5 file.
Upload both the .h5 file and the history file to the main folder of your Google Drive.
Open the Cat_and_Dog_Trained.ipynb in Google Colab and run the cells to connect your Drive and start the analysis.
