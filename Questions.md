## Questions

**Recurrent Neural Networks**

1. What is sequence models? Give the examples of the sequence data.
2. Explain recurrent Neural Network model. Draw simple scheme.
![RNN1](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%201/Building%20a%20RNN/images/Screenshot%202020-05-13%20at%2007.44.00.png)
3. Why using a standard network for a sequence data is a bad idea?
4. Explain how the activation function and the output in each layer (forward propagation) of RNN is calculated. (Intuition)
![RNN2](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%201/Building%20a%20RNN/images/Screenshot%202020-05-13%20at%2007.46.27.png)
5. Explain how backpropagation in RNN works.
![Backprop](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%201/Building%20a%20RNN/images/Screenshot%202020-05-13%20at%2007.47.56.png)
6. Types of RNNs: Many-to-many, Many-to-one, One-to-many. Givу examples of tasks for each of them.
![RNN types](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%201/Building%20a%20RNN/images/Screenshot%202020-05-13%20at%2007.50.00.png)
7. Language model and sequence generation. Types of language models. 
![image](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%201/Building%20a%20RNN/images/Screenshot%202020-05-13%20at%2007.52.04.png)
8. What is sampling in a trained RNN?
![image](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%201/Building%20a%20RNN/images/Screenshot%202020-05-13%20at%2007.54.49.png)
9. Explain the problem of vanishing and exploding gradients. Why it is a problem in RNNs? What are the possible solutions?
10. Gated Recurrent Unit. Draw a simple scheme of GRU. Explain how it works.
![GRU1](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%201/Building%20a%20RNN/images/Screenshot%202020-05-13%20at%2008.00.52.png)
11. GRU and LSTM intuition.
![LSTM](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%201/Building%20a%20RNN/images/Screenshot%202020-05-14%20at%2007.43.33.png)
12.LSTM. LSTM unit. The principles of LSTM, intuition behinf it's construction. 
What pluses of LSTM do you know? When you will use GRU and when you will use LSTM? Advantages of GRU and LSTM
![LSTM2](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%201/Building%20a%20RNN/images/Screenshot%202020-05-14%20at%2007.44.44.png)
13. What is bidirectional RNN? What is Deep RNN?

**More from the quiz**

2. Consider this RNN:
![q1](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%201/Building%20a%20RNN/images/Screenshot%202020-05-14%20at%2007.49.13.png)
This specific type of architecture is appropriate when Tx ... (=,>,<) Ty.
4. You are training this RNN language model. At the t^{th}tth time step, what probability is the RNN calculating?
![q3](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%201/Building%20a%20RNN/images/Screenshot%202020-05-14%20at%2007.49.53.png)
5. You have finished training a language model RNN and are using it to sample random sentences, as follows:
What are you doing at each time step tt? How are output and the input of the next step are connected?
![q4](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%201/Building%20a%20RNN/images/Screenshot%202020-05-14%20at%2008.08.34.png)
6. You are training an RNN, and find that your weights and activations are all taking on the value of NaN (“Not a Number”). What is the cause of this problem (most likely)?
7. Suppose you are training a LSTM. You have a 10000 word vocabulary, and are using an LSTM with 100-dimensional activations a^{<t>}. What is the dimension of Γu at each time step?
8. Here’re the update equations for the GRU. Alice proposes to simplify the GRU by always removing the \Gamma_uΓ I.e., setting \Gamma_uΓ = 1. Betty proposes to simplify the GRU by removing the \Gamma_rΓ I. e., setting \Gamma_rΓ  = 1 always. Which of these models is more likely to work without vanishing gradient problems even when trained on very long input sequences?
![q5](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%201/Building%20a%20RNN/images/Screenshot%202020-05-14%20at%2008.10.44.png)
9. Here are the equations for the GRU and the LSTM: From these, we can see that the Update Gate and Forget Gate in the LSTM play a role similar to _______ and ______ in the GRU. What should go in the the blanks?
![q6](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%201/Building%20a%20RNN/images/Screenshot%202020-05-14%20at%2007.57.34.png)
10. You have a pet dog whose mood is heavily dependent on the current and past few days’ weather. You’ve collected data for the past 365 days on the weather, which you represent as a sequence as x^{<1>}, …, x^{<365>}x. You’ve also collected data on your dog’s mood, which you represent as y^{<1>}, …, y^{<365>}y. You’d like to build a model to map from x \rightarrow yx→y. Should you use a Unidirectional RNN or Bidirectional RNN for this problem?
