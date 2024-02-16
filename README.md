# Handwritten Digit Recognizer

This application allows users to draw a digit on a canvas, and it uses a trained deep learning model to recognize and predict the digit drawn by the user.

![Screenshot 2024-02-17 021242](https://github.com/atugharajohn/digit-recog/assets/92631399/24a725d9-d64a-42b8-b7f1-f3765fb2b0a2)

![Screenshot 2024-02-17 021353](https://github.com/atugharajohn/digit-recog/assets/92631399/ce51fbeb-a96c-4e9e-9921-b4a7c348f49b)

## Requirements
- Python 3.x
- tkinter (usually included with Python)
- keras
- Pillow (PIL)
- numpy

## Installation
1. Clone this repository to your local machine.
2. Install the required dependencies using pip:

```pip install -r requirements.txt```

3. Place your trained model file (`mnist.h5`) in the same directory as the `main.py` file.

## Customization
- You can modify the appearance of the application window, canvas, buttons, and labels by editing the corresponding parameters in the `DrawingApp` class in the `main.py` file.
- You can also customize the drawing mechanism, prediction logic, and model loading process by modifying the respective methods in the `DrawingApp` class.
