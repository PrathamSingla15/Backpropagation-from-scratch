# Backpropagation 
Bakpropagation is an optimization algorithm used for training artificial neural networks (ANNs) in the field of machine learning. The fundamental idea behind backpropagation is to minimize the error in the network's predictions by adjusting the weights of the connections between neurons.

## Here we have concise explanation of it:
1.Forward pass:
 * The input data is fed into the neural network, and the network produces an output.
 * The output is compared to the actual target values using a predefined loss function, which measures the difference between the predicted and actual outputs.
2. Backward pass:
 * The algorithm then works backward through the network to calculate the gradient of the loss function with respect to each weight in the network.
 * The gradient is a measure of how much the error would increase or decrease if a particular weight is adjusted.
3. Weight update:
 * The weights are then updated in the opposite direction of the gradient to minimize the error. This update is performed using an optimization algorithm, often gradient descent.
 * The learning rate determines the size of the step taken during optimization.
