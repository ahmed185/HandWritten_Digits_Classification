HandWritten Digits Classification Model
This project contains a simple handwritten digits classification model built using TensorFlow. The model is designed to classify digits from the MNIST dataset, which includes 28x28 grayscale images of digits ranging from 0 to 9.

Model Architecture
The model is a simple feedforward neural network with the following layers:

Input layer: Flattening the 28x28 input images into a 784-dimensional vector.
Dense layer: 128 neurons with ReLU activation.
Output layer: 10 neurons with softmax activation for classification.
Training
The model is trained using the MNIST dataset, which is automatically downloaded by TensorFlow. The training script includes:

Loading and preprocessing the dataset.
Defining the model architecture.
Compiling the model with an optimizer, loss function, and metrics.
Training the model for a specified number of epochs.
Evaluation
The model is evaluated on a test set from the MNIST dataset. The evaluation script loads the trained model and computes accuracy on the test data.

Results
The model achieves an accuracy of approximately 97% on the MNIST test dataset.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

