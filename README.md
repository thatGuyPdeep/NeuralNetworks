# NeuralNetworks
 
HSL622 - Computation and Cognition
M.Sc. Cognitive Science
Indian Institute of Technology, Delhi

----------------------------------------------------------------------

Dataset: MNIST Handwritten Digits

Description: The MNIST dataset is a classic benchmark for machine learning models. It contains 70,000 examples of handwritten digits (60,000 for training, 10,000 for testing).
Structure:
Each example is a 28x28 grayscale image.
Images are associated with labels indicating the correct digit (0-9).
Processes Involved in Training a Neural Network on MNIST

Forward Propagation

Input: An image of a handwritten digit is fed into the neural network as input.
Layers: The image data is propagated forward through the layers of the network. Within each layer:
Linear Combination: Input values are multiplied by weights and a bias term is added.
Activation Function: A non-linear function (like ReLU or sigmoid) is applied to the result, introducing the ability to model complex patterns.
Output: The output layer produces probabilities for each of the 10 digit classes.
Backpropagation

Error Calculation: The network's prediction (output) is compared to the true label of the image. An error or loss function is used to quantify the difference.
Error Propagation: Through the chain rule, the error is propagated backwards through the network layers. Gradients are calculated, representing how much each weight and bias contributed to the error.
Updating Parameters

Gradient Descent: An optimization algorithm, gradient descent uses the calculated gradients to update the network's weights and biases.
Updates are made in the opposite direction of the gradient, with the goal of reducing the error.
Learning Rate: A hyperparameter that controls the size of the updates made during gradient descent.
Iterative Learning

This process of forward propagation, backpropagation, and parameter updating is repeated over multiple iterations and examples from the MNIST dataset. With each iteration, the neural network adjusts its weights and biases, gradually becoming better at classifying handwritten digits.




# This project is intended for sharing knowledge.

