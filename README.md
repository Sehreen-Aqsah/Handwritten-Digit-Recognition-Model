# Handwritten-Digit-Recognition-Model using CNN
This project implements a Convolutional Neural Network (CNN) to recognize handwritten digits using the MNIST dataset. The trained model is integrated with a simple Tkinter GUI that allows users to draw digits and get real-time predictions.

**Features:**
* Uses Keras with TensorFlow backend for training the CNN model
* Trained on the standard MNIST dataset containing 70,000 images of handwritten digits (0–9)
* Graphical User Interface (GUI) built using Tkinter
* Allows users to draw a digit on a canvas and recognize it using the trained model

**Technologies Used:**
* Python
* Keras
* TensorFlow
* Tkinter
* NumPy

**How It Works**
1. The CNN model is trained using Keras on the MNIST dataset (60,000 training images and 10,000 test images).
2. The trained model is saved as mnist.h5.
3. The GUI (GUI Updated.py) allows users to draw digits in a canvas.
4. The drawing is preprocessed and passed to the model for prediction.
