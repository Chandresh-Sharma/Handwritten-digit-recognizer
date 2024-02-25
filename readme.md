# Digit Recognizer using Convolutional Neural Networks (CNN)

This project consists of three files:

1. `mnist.h5`: This file contains the trained CNN model for recognizing handwritten digits.

2. `train_digit_recognizer.py`: This Python script is used to train the CNN model on the MNIST dataset and save the trained model as `mnist.h5`.

3. `gui_digit_recognizer.py`: This Python script provides a GUI (Graphical User Interface) for users to draw digits and get real-time predictions from the trained model.

## Usage

### Step 1: Training the Model

Run the `train_digit_recognizer.py` script to train the CNN model. This script loads the MNIST dataset, defines the model architecture, trains the model, and saves the trained model as `mnist.h5`.

```bash
python train_digit_recognizer.py
```

### Step 2: Using the GUI for Digit Recognition

Run the `gui_digit_recognizer.py` script to open the GUI application. This GUI allows users to draw digits using the mouse and get real-time predictions from the trained CNN model.

```bash
python gui_digit_recognizer.py
```
Follow the instructions on the GUI to draw digits and see the model's predictions.

## Requirements

- Python 3.x
- Keras
- Tkinter
- numpy
- PIL (Python Imaging Library)
- win32gui (Windows-specific library for capturing screen images)

Ensure you have all the required libraries installed before running the scripts.

**Note:** Make sure to have the `mnist.h5` file in the same directory as the `gui_digit_recognizer.py` script before running it.
