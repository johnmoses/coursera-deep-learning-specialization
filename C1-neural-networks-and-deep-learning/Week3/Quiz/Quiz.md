# Week 3 Quiz

- Which of the following are true? (Check all that apply.) **Notice that I only list correct options.**

    [x] X is a matrix in which each column is one training example.
    [x] a^[2]_4 is the activation output by the 4th neuron of the 2nd layer
    [x] a^\[2\](12) denotes the activation vector of the 2nd layer for the 12th training example.
    [x] a^[2] denotes the activation vector of the 2nd layer.
- The sigmoid function is only mentioned as an activation function for historical reasons. The tanh is always preferred without exceptions in all the layers of a Neural Network. True/False?
    [x] True
    [] False

- Which of these is a correct vectorized implementation of forward propagation for layer l, where 1≤l≤L?

    [x] Z^[l]=W^[l]A^[l−1]+b^[l]
    [x] A^[l]=g^\[l](Z^[l])

- When building a binary classifier for recognizing cats (y=1) vs raccoons (y=0). Is better to use the sigmoid function as activation function for the hidden layers. True/False
    [x] True
    [] False
- Consider the following code:

    ```
    A = np.random.randn(4,5)
    B = np.sum(A, axis = 1)
    ```
    
    What will be y.shape?
    
    `B.shape = (4, 1)`
- Suppose you have built a neural network with one hidden layer and tanh as activation function for the hidden layer. You decide to initialize the weights to small random numbers and the biases to zero. The first hidden layer’s neurons will perform different computations from each other even in the first iteration. True/False?
    [] True
    [x] False

- Logistic regression’s weights should be initialized randomly rather than to all zeros, because if you initialize to all zeros, then logistic regression will fail to learn a useful decision boundary because it will fail to “break symmetry”, True/False?
    [] True
    [x] False

Which of the following are true about the tanh function?
    [] For large values slope is close to zero