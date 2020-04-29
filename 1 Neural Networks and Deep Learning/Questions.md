## Course questions

### Week 3 - Shallow neural networks

1. What input/hidden/output layers of NN are ?
2. Describe the math of single Neuron.
3. Activation function. Types of activation functions.
4. Why do you need non-linear activation function?
5.  Pros and Cons of sigmoid, tanh, ReLU, Leaky ReLU
6. Backpropogation simple explanation
![ex](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/1%20Neural%20Networks%20and%20Deep%20Learning/week%203/images/AC78FD38-C896-4654-B6FA-B4520BE8797C.png)
7. Why do you need random initialization in NN?

**More from the quiz**

8. The tanh activation usually works better than sigmoid activation function for hidden units because the mean of its output is closer to zero, and so it centers the data better for the next layer. True/False?
9. Suppose you have built a neural network. What will happen if you decide to initialize the weights and biases to be zero?
10. You have built a network using the tanh activation for all the hidden units. You initialize the weights to relative large values, using np.random.randn(..,..)*1000. What will happen?


### Week 4 - Shallow neural networks

1. How many layers does this network have?
![layers](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/1%20Neural%20Networks%20and%20Deep%20Learning/week%204/images/8E001A70-3705-420B-B3FC-CEE7D542D13D.png)
2. General forward propagation equation
3. General backward propagation equation
4. Name the dimensions of W and b in each layer:
![NN](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/1%20Neural%20Networks%20and%20Deep%20Learning/week%204/images/D571455D-EE09-4AE2-87CF-6EB956001E55.png)
5. Explain forward and backward propagation intuition in NN.
![b_ex](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/1%20Neural%20Networks%20and%20Deep%20Learning/week%204/images/FCD17C4E-E0D0-403C-AFF5-10C66DFFD081.png)
6. Forward and backward propagation formulas.
7. What are hyperparams in NN?

**More from the quiz**

8. During forward propagation, in the forward function for a layer l you need to know what is the activation function in a layer (Sigmoid, tanh, ReLU, etc.). During backpropagation, the corresponding backward function also needs to know what is the activation function for layer l, since the gradient depends on it. True/False?

9. There are certain functions with the following properties: (i) To compute the function using a shallow network circuit, you will need a large network (where we measure size by the number of logic gates in the network), but (ii) To compute it using a deep network circuit, you need only an exponentially smaller network. True/False?
