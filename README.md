# Handwritten-Digit-Classifier-APP
This project is for my AICTE Microsoft AI Azure Internship conducted by Edunet Foundation.

# HDC Main Code(CNN).ipynb
Description:
This Jupyter Notebook (.ipynb file) contains the complete image processing pipeline and Convolutional Neural Network (CNN) model training workflow for the application. 
It serves as the core component responsible for image classification and prediction within the app.

# Handwritting_digit_classifier_app.ipynb
The application classifies handwritten digits (0–9) using a trained deep learning model. It features a Tkinter-based GUI, enhanced with ttk.Style for better visuals. 
Users can input images via file upload or freehand drawing using ImageGrab and PIL.Image. Input images are preprocessed to 28x28 pixels to match the model's requirements.
Predictions are displayed on the GUI along with confidence scores or visual plots using Matplotlib and Seaborn.These plots are embedded in the interface via FigureCanvasTkAgg. 
The app includes interactive elements like message boxes and styled buttons, as well as a loading screen during model initialization.

# mnist_digit_classifier_final.keras
After training, the final model is saved in this Keras file. This saved model serves as the backbone for the application's prediction functionality, allowing seamless integration with the app for real-time digit classification.

# MNIST Sample Images for Testing and Input
This folder contains sample images from the MNIST dataset, which can be used as input for the application to perform digit prediction. These images are also useful for testing and validating the model's performance within the app environment.

Ghost Script Link: https://www.ghostscript.com/
(*NOTE-Please install Ghost Script to use ‘Drawing canvas’ of the app properly. Please add path of Ghost Script bin folder in environment variable)
