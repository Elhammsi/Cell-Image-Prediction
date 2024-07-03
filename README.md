 
# Cell Image Classification Project
## Overview
This project focuses on classifying cell images as infected (parasitized) or uninfected using Convolutional Neural Networks (CNNs). The goal is to leverage deep learning techniques to build a robust model that can accurately predict the health status of cells based on their images. The project utilizes TensorFlow and Keras libraries to develop, train, and evaluate the CNN model.

## Project Structure
data/: Contains the dataset of cell images, divided into train and test subfolders, each containing Uninfected and Parasitized images.
notebooks/: Jupyter notebooks used for data exploration, preprocessing, model training, and evaluation.
models/: Saved models and weights for easy loading and inference.
scripts/: Python scripts for data preprocessing, model training, and evaluation.
README.md: This file, providing an overview and instructions for the project.
requirements.txt: List of dependencies required to run the project.
## Dataset
The dataset is organized into the following structure:

train/
Uninfected/: Images of uninfected cells.
Parasitized/: Images of parasitized (infected) cells.
test/
Uninfected/: Images of uninfected cells.
Parasitized/: Images of parasitized (infected) cells.
Requirements
To run this project, you will need the following dependencies:

Python 3.7+
TensorFlow 2.x
Keras
NumPy
Pandas
Matplotlib
Scikit-learn
Jupyter Notebook (optional, for running the notebooks)

### 1. Data Preprocessing
Before training the model, the cell images need to be preprocessed. This step includes resizing images, normalizing pixel values, and augmenting the training dataset to improve model robustness. Run the preprocessing script:
 
### 2. Model Training
Train the CNN model using the preprocessed data. The training script initializes the model, compiles it, and trains it using the training dataset. Run the training script:
 
### 3. Model Evaluation
After training, evaluate the model's performance on the test set. The evaluation script loads the trained model and computes metrics such as accuracy, precision, recall, and F1-score. Run the evaluation script:

 
 


### Results
The results of the model training and evaluation, including accuracy and loss plots, confusion matrix, and classification report, are documented in the notebooks/results.ipynb notebook.

### Conclusion
This project demonstrates the application of CNNs using TensorFlow and Keras to classify cell images as infected (parasitized) or uninfected. The developed model can be further improved by experimenting with different architectures, hyperparameters, and data augmentation techniques.

 






