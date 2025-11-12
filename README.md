# ACML Homework: Neural Networks #
In this project, we have to implement a neural network. The implementation can be made in any language of our choice:
Java, MATLAB, Octave, Python, Prolog (for the extra challenge) ... (*we decided to use Python*), but without relying on high-
level libraries such as Keras, PyTorch, Theano, Tensorflow, Deeplearning4J, the MATLAB Neural Network Toolbox,
etc. 

The goal of the implementation is to produce and train a network with 3 layers: input - hidden - output. Both the
input layer and the output layer will have 8 nodes, the hidden layer only 3 nodes (+biases).
The learning examples will each have 7 zeros and 1 one in them (so there will be only 8 different learning examples,
and you will have to repeat them), and the output the network should learn is exactly the same as the input. So when
the input layer is given < 0, 0, 0, 1, 0, 0, 0, 0 > as input, the output to aim for is also < 0, 0, 0, 1, 0, 0, 0, 0 >.
Try to get your network to learn this reproducing function on the 8 different learning examples.
Then study the weights and the activations of the hidden nodes of your network and try to interpret them.
