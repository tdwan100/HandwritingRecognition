# Handwritten Digit Classifier GUI

This project is a Handwritten Digit Classifier with a graphical user interface (GUI) developed using Python. The GUI allows users to draw a digit on a canvas, and the classifier will predict the drawn digit using a pre-trained Random Forest model.

## Requirements

To run this project, you'll need Python 3.x and the following dependencies:

- numpy
- pandas
- scikit-image
- scikit-learn
- Pillow (PIL)
- tkinter (included with most Python installations)

You can install the required packages using pip:

```
pip install numpy pandas scikit-image scikit-learn Pillow
```

## Getting Started

1. Clone this repository to your local machine or download the `HandwritingRecognition.py` file directly.

2. Download the dataset: The project uses the "MNIST Handwritten Digits" dataset. You can download it from Kaggle or any other source. Place the `mnist_train.csv` file in the same directory as `HandwritingRecognition.py`.

3. Run the GUI: Execute the following command to start the GUI:

```
python HandwritingRecognition.py
```

## How to Use

1. When the GUI window opens, you will see a canvas where you can draw a digit using your mouse.

2. To draw a digit, click and hold the left mouse button while moving the mouse over the canvas. Release the button when you are done drawing.

3. Click the "Classify Number" button to predict the drawn digit.

4. The predicted digit will be displayed below the canvas.

5. Click the "Reset Everything" button to clear the canvas and draw a new digit.

## How It Works

- The drawn digit is captured by the canvas and stored as a 2D array of pixels.

- The drawn image is resized to a 28x28 size image and formatted to match the format used during training.

- The pre-trained Random Forest classifier predicts the digit based on the formatted image.

- The predicted digit is displayed on the GUI.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License

## Acknowledgments

- The MNIST dataset was used for training the model.
- The scikit-learn library was used for machine learning tasks.
- The tkinter library was used for building the GUI.
