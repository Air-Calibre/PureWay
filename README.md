# AirCalibre
Air pollution is a global issue that poses a significant threat to human health and the environment, and measuring its concentration levels in the atmosphere is essential to reduce it. This project explores the use of image analysis and deep learning techniques to predict PM 2.5 levels.


# Air_Pollution_detection_using_Inception_V3(Transfer_Learning)Model
This file contains code for performing transfer learning using the Inception V3 model in Keras. The project demonstrates how to fine-tune a pre-trained Inception V3 model on a custom dataset.


## Project Structure

This notebook contains the following steps:

1. Importing required libraries
2. Assigning dataset paths
3. Importing Inception V3 layers and adding a preprocessing layer to the input
4. Creating the model object
5. Assigning cost function and optimization method to the model
6. Performing preprocessing on the input data
7. Fitting the model

## Requirements

- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib 

## Usage

1. Clone this repository
2. Open the `Transfer_Learning_InceptionV3.ipynb` notebook in Google Colab or Jupyter Notebook
3. Follow the steps in the notebook to train the model on your custom dataset

## Dataset

The Model was trained with images from various locations across Mumbai, Thane, Vasai, Ratnagiri. The model in this article has been implemented using the Keras deep learning framework.

## Results


The five classes of this dataset have been labeled such that the general masses can easily derive meaning from the output image to take appropriate action, so as to use air-pollution masks, trying to stay indoors, using household air-filters, or to travel without need of pollution safety measures (in-case of Good to Moderate PM 2.5 levels) depending on the air quality levels .
An example output indicating the PM 2.5 level


## Future Work


The future goal of this research is to integrate the model into a mobile application, allowing users to take pictures of their surroundings and receive an estimated air quality reading. The application will also upload the user's location and predicted air quality to a centralized database. This database will be accessible within the application, allowing users to visualize the predicted air quality of all users on a world map. The application will be open source, allowing for community-driven development and improvement.

