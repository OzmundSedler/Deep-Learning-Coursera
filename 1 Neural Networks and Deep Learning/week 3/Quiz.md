## Quiz

## Shallow Neural Networks

1. **Which of the following are true? (Check all that apply.)**
   
- a[2](12) denotes the activation vector of the 2nd layer for the    12th training example.
- a[2] denotes the activation vector of the 2nd layer.
- X is a matrix in which each column is one training example.
- a[2]4 is the activation output by the 4th neuron of the 2nd layer

2. **The tanh activation usually works better than sigmoid activation function for hidden units because the mean of its output is closer to zero, and so it centers the data better for the next layer. True/False?**

- True

3. **Which of these is a correct vectorized implementation of forward propagation for layer l, where 1≤l≤L?**

- Z[l]=W[l]A[l−1]+b[l]
- A[l]=g[l](Z[l])

4. **You are building a binary classifier for recognizing cucumbers (y=1) vs. watermelons (y=0). Which one of these activation functions would you recommend using for the output layer?**

- sigmoid

5. **Consider the following code:
A = np.random.randn(4,3)
B = np.sum(A, axis = 1, keepdims = True)
What will be B.shape? (If you’re not sure, feel free to run this in python to find out).**

- (4, 1)

6. **Suppose you have built a neural network. You decide to initialize the weights and biases to be zero. Which of the following statements are True? (Check all that apply)**

- Each neuron in the first hidden layer will perform the same computation. So even after multiple iterations of gradient descent each neuron in the layer will be computing the same thing as other neurons.

7. **Logistic regression’s weights w should be initialized randomly rather than to all zeros, because if you initialize to all zeros, then logistic regression will fail to learn a useful decision boundary because it will fail to “break symmetry”, True/False?**

- False

8. **You have built a network using the tanh activation for all the hidden units. You initialize the weights to relative large values, using np.random.randn(..,..)*1000. What will happen?**

- This will cause the inputs of the tanh to also be very large, thus causing gradients to be close to zero. The optimization algorithm will thus become slow.

9. **Consider the following 1 hidden layer neural network:**

Which of the following statements are True? (Check all that apply).

- b[1] will have shape (4, 1)
- W[1] will have shape (4, 2)
- W[2] will have shape (1, 4)
- b[2] will have shape (1, 1)

10. **In the same network as the previous question, what are the dimensions of Z[1] and A[1]?**

- Z[1] and A[1] are (4,m)