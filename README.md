# Notes


Hyperparameter Optimization: https://alykhantejani.github.io/images/gradient_descent_line_graph.gif

Gradient Descent: https://hackernoon.com/dl03-gradient-descent-719aff91c7d6

Chain Rule in differentiation (for backpropogation): http://www.mathcentre.ac.uk/resources/uploaded/mc-ty-chain-2009-1.pdf

Backpropogation paper 1996: http://www.iro.umontreal.ca/~pift6266/A06/refs/backprop_old.pdf

https://www.reddit.com/r/tensorflow/comments/dej9zd/visualizing_a_neural_network_created_using_tensor/
https://preview.redd.it/z516nyulc4r31.gif?format=mp4&s=7da7884ef4b131d8128a95fab800bee395b664ec

The tanh activation usually works better than sigmoid activation function for hidden units because the mean of its output is closer to zero, and so it centers the data better for the next layer. 

#Install a conda package in the current Jupyter kernel
import sys
!conda install --yes --prefix {sys.prefix} psycopg2

Deep Learning: Is basically learning input to output mapping using complex functions.

Applied ML is a highly iterative process.

Baye's Error = Human Error (e.g. classifying a blurry image by a human, etc.)

High Bias Problem (Underfitting): Try bigger (more neurons) & Deeper (more layers) Network; Train GD longer; Search for NN Architecture

High Variance Problem (Overfitting): Collect more training data; Try regularization techniques; Search for NN Architecture

If you are 'regularizing' NN, then training bigger network will never hurt: Regularization will take care of bias-variance trade off problem; Might add bias sometimes but not a major concern. Fix overfitting using Regularization.

L2 Regularization is used more comonly in Deep NN. L1 Regularization creates a sparse metrix of W (weights) and includes a lot of zeros. 
L2 regularization is also called 'weight decay'.

With high lambda (regularization parameter), weights will be close to 0. That will make a lot of neurons effect = 0 or less effect; network will become simpler (but still deep); and thus high variance network becomes high bias and then eventually learns function which is 'just right'.




