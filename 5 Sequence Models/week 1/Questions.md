## Questions

**Recurrent Neural Networks**

1. What is sequence models? Give the examples of the sequence data.
2. Explain recurrent Neural Network model. Draw simple scheme.
![RNN1]
3. Why using a standard network for a sequence data is a bad idea?
4. Explain how the activation function and the output in each layer (forward propagation) of RNN is calculated. (Intuition)
![RNN2]
5. Explain how backpropagation in RNN works.
![Backprop]
6. Types of RNNs: Many-to-many, Many-to-one, One-to-many
![RNN types]  
7. Language model and sequence generation. Types of language models. 
![image]
8. What is sampling in a trained RNN?
![image]
9. Explain the problem of vanishing and exploding gradients. Why it is a problem in RNNs? What are the possible solutions?
10. Gated Recurrent Unit. Draw a simple scheme of GRU. Explain how it works.
![GRU1]
11. GRU and LSTM intuition.
![LSTM]
12.LSTM. LSTM unit. The principles of LSTM, intuition behinf it's construction. 
What pluses of LSTM do you know? When you will use GRU and when you will use LSTM? Advantages of GRU and LSTM
![LSTM2]
13. What is bidirectional RNN? What is Deep RNN?

**More from the quiz**

2. **Consider this RNN: This specific type of architecture is appropriate when:**
![q1]
3. **To which of these tasks would you apply a many-to-one RNN architecture? (Check all that apply).**
![q2]
4. **You are training this RNN language model. At the t^{th}tth time step, what is the RNN doing? Choose the best answer.**
![q3]
5. **You have finished training a language model RNN and are using it to sample random sentences, as follows:
What are you doing at each time step tt?**
![q4]
6. **You are training an RNN, and find that your weights and activations are all taking on the value of NaN (“Not a Number”). Which of these is the most likely cause of this problem?**
7. **Suppose you are training a LSTM. You have a 10000 word vocabulary, and are using an LSTM with 100-dimensional activations a^{<t>}. What is the dimension of Γu at each time step?**
8. **Here’re the update equations for the GRU. Alice proposes to simplify the GRU by always removing the \Gamma_uΓ I.e., setting \Gamma_uΓ = 1. Betty proposes to simplify the GRU by removing the \Gamma_rΓ I. e., setting \Gamma_rΓ  = 1 always. Which of these models is more likely to work without vanishing gradient problems even when trained on very long input sequences?
![q5]
9. Here are the equations for the GRU and the LSTM: From these, we can see that the Update Gate and Forget Gate in the LSTM play a role similar to _______ and ______ in the GRU. What should go in the the blanks?
![q6]
10. You have a pet dog whose mood is heavily dependent on the current and past few days’ weather. You’ve collected data for the past 365 days on the weather, which you represent as a sequence as x^{<1>}, …, x^{<365>}x 
<1>
 ,…,x 
<365>
 . You’ve also collected data on your dog’s mood, which you represent as y^{<1>}, …, y^{<365>}y 
<1>
 ,…,y 
<365>
 . You’d like to build a model to map from x \rightarrow yx→y. Should you use a Unidirectional RNN or Bidirectional RNN for this problem?