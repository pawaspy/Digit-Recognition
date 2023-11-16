# Simple MNIST Neural Network from Scratch 🧠

This repository contains the implementation of a simple two-layer neural network for digit recognition using the MNIST dataset. It's designed as an instructional example to help you understand the underlying math of neural networks.

## Prerequisites 😎

To run this code, you'll need the following:

* Python 3.x
* NumPy
* Pandas
* Matplotlib

## Installation 📦

You can install the required dependencies using the following commands:

`pip install numpy pandas matplotlib`

## Running the Code 🏃‍♂️
To run the code, simply clone the repository and execute the following command:

`python3 mnist_nn.py`

This will train the neural network on the MNIST dataset and print the accuracy of the predictions.

## Understanding the Code 🤓

The code is divided into several functions, each responsible for a specific step in the neural network training process:

* `init_params()`: Initializes the neural network parameters.
* `ReLU()`: Implements the ReLU activation function.
* `softmax()`: Implements the softmax activation function.
* `forward_prop()`: Performs forward propagation through the neural network.
* `one_hot()`: Converts labels to one-hot vectors.
* `deriv_ReLu()`: Computes the derivative of the ReLU activation function.
* `back_prop()`: Performs backpropagation to compute the gradients.
* `update_params()`: Updates the neural network parameters based on the gradients.
* `get_predictions()`: Converts network outputs to predicted labels.
* `get_accuracy()`: Calculates the accuracy of the predictions.
* `gradient_descent()`: Trains the neural network using gradient descent.

## Contributing 🤝

If you have any questions or suggestions, feel free to open an issue or pull request. Your contributions are welcome!

I hope this README file is helpful and informative. Please let me know if you have any other questions.

