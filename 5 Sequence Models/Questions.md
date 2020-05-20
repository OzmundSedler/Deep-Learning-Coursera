## Week 1 - Recurrent Neural Networks

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


## Week 2 - Natural Language Processing & Word Embeddings

1. What is word embeddings ?
2. How transfer learning is connected to the word embeddings?
3. What is finetuning?
4. Cosine similarity. Formula. Where it can be applied?
5. Bag of words algorithm
6. A neural probabilistic language model 
![image](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%202/Emojify/images/Screenshot%202020-05-15%20at%2007.48.53.png) 
![image2](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%202/Emojify/images/Screenshot%202020-05-15%20at%2007.49.31.png)
7. What is skip-gram model?
8. Word2Vec algorithm. 
9. Intuition behind negative sampling
![image3](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%202/Emojify/images/Screenshot%202020-05-15%20at%2007.52.28.png)
10. GloVe word vectors 
![GloVe](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%202/Emojify/images/Screenshot%202020-05-15%20at%2007.54.02.png) 
![GloVe2](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%202/Emojify/images/Screenshot%202020-05-15%20at%2007.54.06.png)
11. Give an example of sentiment classification model and how it can be applied.
![img](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%202/Emojify/images/Screenshot%202020-05-15%20at%2007.55.03.png)

**More from the quiz**

12. Suppose you learn a word embedding for a vocabulary of 10000 words. Then the embedding vectors should be 10000 dimensional, so as to capture the full range of variation and meaning in those words. True/False?
13. Suppose you download a pre-trained word embedding which has been trained on a huge corpus of text. You then use this word embedding to train an RNN for a language task of recognizing if someone is happy from a short snippet of text, using a small training set.
    Then if the word “ecstatic” does not appear in your small training set, how your RNN will recognize “I’m ecstatic” and what label it will probably assign to it? Why?
14. Give an example of equations you think should hold for a good word embedding. (e_{boy} - e_{girl} ≈ e_{brother} - e_{sister})
15. When learning word embeddings, we create an artificial task of estimating P(target \mid context)P(target∣context). It is okay if we do poorly on this artificial prediction task; the more important by-product of this task is that we learn a useful set of word embeddings. True/False?
16. In the word2vec algorithm, you estimate P(t∣c), where tt is the target word and cc is a context word. How are tt and cc chosen from the training set? 


## Week 3 - Sequence models & Attention mechanism

1. Sequence to sequence model. Encoding and decoding. 
2. How the translation is picked? Why using a conditional language model instead of a greedy?
3. Explain beam search algorithm. What beam width means? 
4. How error analysis on beam search is conducted? Give an example.
5. What is Bleu Score? Pros and Cons of it?
6. Attention model intuition. The problem of long sentences. General mechanism of work.
![image](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%203/Machine%20Translation/images/Screenshot%202020-05-19%20at%2008.04.34.png)
7. Explain how attention model works in general. How attention is computed?
![img1](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%203/Machine%20Translation/images/Screenshot%202020-05-19%20at%2008.07.29.png)
![img2](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%203/Machine%20Translation/images/Screenshot%202020-05-19%20at%2008.07.53.png)
8. Speech recognition basics.  How audio to transcript can be implemented?
![img3](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%203/Machine%20Translation/images/Screenshot%202020-05-20%20at%2008.04.14.png)
9. Trigger word detection algorithm.
![img4](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/5%20Sequence%20Models/week%203/Machine%20Translation/images/Screenshot%202020-05-20%20at%2008.05.24.png)


**More from the quiz**

10. In beam search, if you increase the beam width BB, how speed, memory usage and quality of the solution will change?
11. What will happen, if we will carry out beam search without using sentence normalization?
12. Under the CTC model, identical repeated characters not separated by the “blank” character (_) are collapsed. Under the CTC model, what does the following string collapse to?
__c_oo_o_kk___b_ooooo__oo__kkk 

