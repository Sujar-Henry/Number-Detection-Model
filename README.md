# MNIST Digit Classifier

This project is a digit classification model trained on the MNIST dataset. It includes a drawing application for testing the model by drawing digits and predicting their values.

## Project Structure

```
drawn_digit.png
main.ipynb
mnist_digit_classifier.pth
testSet/
    img_1.jpg
    img_10.jpg
    ...
```

- **`main.ipynb`**: Contains the code for loading the MNIST dataset, training the model, and running the drawing application.
- **`mnist_digit_classifier.pth`**: Pre-trained PyTorch model for digit classification.
- **`data/MNIST/raw/`**: Contains raw MNIST dataset files.
- **`testSet/`**: Contains test images for evaluating the model.
- **`drawn_digit.png`**: Stores the digit drawn in the application for prediction.

## Features

- **Train and Test**: The model is trained on the MNIST dataset and can be tested using the test set or custom images.
- **Drawing Application**: Allows users to draw digits and predict their values using the trained model.

## Requirements

- Python 3.8+
- PyTorch
- torchvision
- pygame

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Number-Detection-Model
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Train the Model
Run the `main.ipynb` notebook to train the model on the MNIST dataset.

### Test the Model
Use the test images in the `testSet/` directory or draw custom digits using the drawing application.

### Run the Drawing Application
Execute the following code in the notebook:
```python
run_drawing_app()
```
Press:
- **`c`** to clear the canvas
- **`p`** to predict the digit
- **`q`** to quit the application

## Example Predictions

- **Drawn Digit**: `drawn_digit.png`
- **Prediction**: `The model predicts the digit is: 3`

## License

This project is licensed under the MIT License.
