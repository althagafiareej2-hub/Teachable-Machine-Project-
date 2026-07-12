# Teachable Machine Project

## Image Classification using Google Teachable Machine, TensorFlow (Keras), and Python

## Project Overview

This project demonstrates an image recognition model created using Google Teachable Machine. The model was trained to classify images into two different classes: Rabbit and Hedgehog.

After training the model, it was exported in TensorFlow (Keras) format. A Python script was developed to load the trained model, process an input image, and predict the correct class with the confidence score.

## Project Objectives

- Create an image classification model using Google Teachable Machine.
- Train the model using images from two different classes.
- Export the trained model in TensorFlow (Keras) format.
- Use Python to load the model and perform image prediction.
- Test the model accuracy by using a new input image.

## Tools and Technologies

- Google Teachable Machine: Used to create and train the image recognition model.
- TensorFlow / Keras: Used to load and run the trained model.
- Python: Used to develop the prediction script.
- Anaconda: Used to manage the Python environment and install required libraries.
- Visual Studio Code: Used to write and execute the Python code.
- GitHub: Used to store and document the project files.

## Project Files

The project contains the following files:

- **keras_model.h5**: The trained TensorFlow (Keras) model exported from Google Teachable Machine.
- **labels.txt**: A file containing the names of the trained classes.
- **task1AI.py**: Python script used to load the model, process the image, and display the prediction result.
- **images.jpg**: The test image used for prediction (Rabbit image).
- **class.jpg**: The class images used for training and comparison between Rabbit and Hedgehog classes.
- **output.png**: Screenshot showing the prediction result after running the Python script.
- **README.md**: Documentation explaining the project and implementation steps.

## Implementation Steps

1. Created an image classification model using Google Teachable Machine.
2. Added two image classes: Rabbit and Hedgehog.
3. Trained the model using the collected class images.
4. Evaluated the model performance.
5. Exported the trained model in TensorFlow (Keras) format.
6. Created a Python environment using Anaconda.
7. Installed the required libraries such as TensorFlow, Keras, Pillow, and NumPy.
8. Developed a Python script to load the model and predict the class of a new image.
9. Tested the model using a Rabbit image as an input.

## How to Run the Project

1. Open the project folder using Visual Studio Code.
2. Activate the Anaconda environment.
3. Make sure all required files are located in the same project folder.
4. Run the Python script using the following command:
   bash
   **python task1AI.py**

   ## Results and Prediction Result

The model was tested using a new input image. The test image was a Rabbit, while the trained classes were Rabbit and Hedgehog.

After running the Python script, the model successfully recognized the image and predicted it as a Rabbit with a confidence score.

The class images used for training (Rabbit and Hedgehog comparison) are attached as **class.jpg**, and the prediction output screenshot is attached as **output.png**.

```bash
python task1AI.py
