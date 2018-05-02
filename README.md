# MNIST Classification with a Neural Network
***
In this script, a neural network consisting of one input layer (784 Neurons), three hidden layers (128/72/72 Neurons), and one output layer (10 Neurons) is used to classify handwritten digits. The input values are the grayscale pixel values of 28x28 images of handwritten digits. The output neurons indicate to which of the 10 digit classes (0 - 9) the input is expected to belong. The network is trained in a classic stochastic gradient descent manner, with sigmoids as activation functions and the sum of squared errors of prediction (SSE) is the loss function which is optimised.



## Data
***
In order to run the script, you need the MNIST data in the csv file format. You can download the test and train data set e.g. from the following link: https://pjreddie.com/projects/mnist-in-csv/

